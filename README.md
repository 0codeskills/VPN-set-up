# VPN set up

## Objective

The  requirements for this project are two linux Virtual Machines and OpenVPN software. One of the VMs will be set up as VPN server and another one as VPN client, which will allow to test the VPN connectivity and configuration.

### Skills Learned

- Installation of OpenVPN server on Kali Linux VM.
- Configuration of OpenVPN server.
- Configuration od OpenVPN client.
- Testing VPN connection.

### Tools Used

- Kali Linux virtual machine as controlled environment.
- OpenVPN software.
- Linux terminal to install and configure OpenVPN.

## Steps

#### OpenVPN Installation

1. Make sure that system in updated by running the following command.

<img width="439" height="120" alt="image" src="https://github.com/user-attachments/assets/015b9f2b-c507-434b-835e-1588b3bbbdad" />

2. Next step is to install OpenVPN and easy-rsa software

<img width="437" height="129" alt="image" src="https://github.com/user-attachments/assets/6675d176-4095-4e72-a7dc-cef8c8ea4933" />

3. The following commands will create a folder in your home directory, copy the content /usr/share/easy-rsa folder to the created folder and we wil switch to the new directory.

<img width="442" height="217" alt="image" src="https://github.com/user-attachments/assets/639d2feb-46d3-446b-b52a-de6660e0df55" />

#### Building CA

1. We will now intiate PKI evironment by running the command below, which will allow us to create CA.

<img width="701" height="409" alt="image" src="https://github.com/user-attachments/assets/2f3ab2a6-ed49-43e0-8669-283bcf99baf3" />

2. We will now build the CA, set a passphrase and assign a hostname to the CA.

<img width="1022" height="721" alt="image" src="https://github.com/user-attachments/assets/25e5c79c-0beb-4703-bec7-180ccbc6dd8f" />

3. Next we will generate server certificate and the key.

<img width="1804" height="539" alt="image" src="https://github.com/user-attachments/assets/142732fd-3510-4fa4-a8ca-2228f7fdc6d7" />

4. Now we will sign the server certificate with the CA.

<img width="728" height="681" alt="image" src="https://github.com/user-attachments/assets/2b065bdf-897e-4c2e-87e0-6fb834bc8b54" />
