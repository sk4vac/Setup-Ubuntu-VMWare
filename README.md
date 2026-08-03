# Setup Ubuntu VMWare

### Hello World

<img width="1191" height="842" alt="image" src="https://github.com/user-attachments/assets/2573fab2-c3c2-4861-b775-980f8ac28cc2" />

In this repository you'll learn about how to install and setup Linux Ubuntu Distro properly, Ubuntu is one of the most popular distro and have a very large comunity base, Ubuntu is like the first Linux distro you must try.

### Prerequisite

1. Ubuntu 26.04 Live Server Amd64
2. VMWare Workstation Full 26H1
3. Understanding of [PNETLab & VMware Setup](https://github.com/sk4vac/PNETLab-Setup-VMWare)

## Installation Guide

### Step 1

<img width="1366" height="734" alt="image" src="https://github.com/user-attachments/assets/8d414950-adb5-4294-b836-ec04d4407d8b" />

Open your VMWare and choose `Create a New Virtual Machine`

### Step 2

<img width="427" height="433" alt="image" src="https://github.com/user-attachments/assets/28de9159-9503-40ab-aabf-5846ffe832d1" />

Choose `Typical (Recommended)`

### Step 3

<img width="426" height="429" alt="image" src="https://github.com/user-attachments/assets/c75a88f5-938b-4aa5-ac77-02aa0cecb421" />

Choose your Ubuntu ISO File location.

### Step 4

<img width="431" height="433" alt="image" src="https://github.com/user-attachments/assets/4fd626bf-0d3d-41b2-80e7-997b818dcf4b" />

Rename the Ubuntu VM name and choose your desired place to store Ubuntu VHD (Virtual Hard Disk)

### Step 5

<img width="433" height="428" alt="image" src="https://github.com/user-attachments/assets/9900431d-1143-4b78-a3d6-7a361e33335f" />

Configure your VHD Size and choose `Store Virtual Disk as a Single File`

### Step 6

<img width="430" height="428" alt="image" src="https://github.com/user-attachments/assets/a3523276-4c44-4ef2-8f26-70e774ed45c8" />

Customize your VM Hardware
- Minimum RAM 1.5GB
- Minimum Processor 2 With 1 Core Each
- NAT Adapter

And choose finish, after that the VM will starting and wait until it's finish booting

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/1fb9a8db-d9f7-4b18-a393-3f44fa9540f9" />

## OS Installation

### Step 1

<img width="1366" height="737" alt="image" src="https://github.com/user-attachments/assets/ee5f07a2-5b56-412a-9d55-4ceb844e217c" />

Choose your desired languange I prefer `English`

### Step 2

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/b8d8dbfd-b443-4fcc-a549-a46679f99e8b" />

Configure your Keyboard I prefer default

### Step 3 

<img width="1366" height="739" alt="image" src="https://github.com/user-attachments/assets/a8d02cae-3c4f-4169-8b27-449229ee22ff" />

I recommended you to choose `Ubuntu Server` default installation.

### Step 4

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/3dea0a85-805a-4a64-a48c-98b2abc2f59c" />

Continue this step!

### Step 5

<img width="1366" height="740" alt="image" src="https://github.com/user-attachments/assets/8cd5dcde-00cc-4a51-aa90-a820e062d559" />

If you have it, type it, if not skip it.

### Step 6

<img width="1366" height="740" alt="image" src="https://github.com/user-attachments/assets/f335b39a-3a09-401a-893c-34d6b82e28b7" />

Wait until the test finished and continue.

### Step 7

<img width="1366" height="737" alt="image" src="https://github.com/user-attachments/assets/e7374756-b3d1-48ec-b90a-d1a4e2168988" />

Configure this step like the Image.

### Step 8

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/fb4ee94e-a151-4ecc-a53f-d88625af9d17" />

Continue this steps, use default settings!

### Step 9

<img width="1366" height="739" alt="image" src="https://github.com/user-attachments/assets/7ff221d7-afce-4120-ba48-8c40aad2eb6c" />

Choose `Continue`

### Step 10

<img width="1366" height="737" alt="image" src="https://github.com/user-attachments/assets/99b34c37-65a2-4a0e-bcdf-8c437ef07c9d" />

Configure your name here.

### Step 11

<img width="1366" height="740" alt="image" src="https://github.com/user-attachments/assets/06515939-cd63-4c87-9e0e-b55e53d4f7c8" />

Skip these step.

### Step 12

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/035cccb6-531a-4fd0-a9f4-8d294486d62b" />

Check the `Install OPENSSH Server` Box and continue.

### Step 13

<img width="1366" height="735" alt="image" src="https://github.com/user-attachments/assets/991ae684-bec5-4d80-80b6-d39b08cc6de3" />

Leave it empty, we will install it later when we need it.

### Step 14

<img width="1366" height="741" alt="image" src="https://github.com/user-attachments/assets/398ef505-c3d9-4dcc-ba33-ce10566f89d3" />

Wait until finished.

### Step 15

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/e894e771-fd5b-45f8-8bf6-b41527395ec7" />

When it's Finished. Reboot Now! Then LOG IN!

## Package Installation

1. run `sudo apt update`
2. run `sudo apt upgrade`
3. run `sudo apt autoremove`

Congratulation! You just installed the base system of Ubuntu Server
