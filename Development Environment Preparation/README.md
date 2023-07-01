# Development Enviroment Preparation
## 1. ModusToolbox Installation and Firmware Updates
### 1.1 ModusToolbox Installation
#### 💻 System Requirement

    - Windows 7 64-bit / Windows 10 64-bit
    - macOS10.x
    - UbuntuLinux18LTS

#### 📀 Download the Software
Go to the Cypress ModusToolbox website (www.cypress.com/modustoolbox) and download your appropriate software from your platform: 

    - Windows:ModusToolbox_1.1.0.<build>-windows-install.exe
    - Linux:ModusToolbox_1.1.0.<build>-linux-install.tar.gz
    - macOS:ModusToolbox_1.1.0.<build>-osx-install.pkg

![Alt text](Img/image.png)

### 1.2 Firmware Updates
#### 💻 For MacOS
##### Checking fw’s version
```
$ cd /Applications/ModusToolbox/tools_3.0/fw-loader/bin/
$ ./fw-loader --device-list
```
![Alt text](Img/image-1.png)

##### Update firmware
```
$ ./fw-loader --update-kp3
```
![Alt text](Img/image-2.png)

#### For Windowns 
Open modus-shell 
![Alt text](Img/image-3.png)




### 1.3 Adding the BDH Code Template
```
$ cd 
$ cd ~/.modustoolbox/
$ echo 'https://raw.githubusercontent.com/Advance-Innovation-Centre-AIC/mtb2-bdh-academy-manifests/master/bdh-academy-super-manifest.xml' > ~/.modustoolbox/manifest.loc
```
![Alt text](Img/image-4.png)

## 2. Eclipse IDE Development Tools and Project Creator
### 1. Open ModusToolbox Tool 
![Alt text](Img/image-5.png)

### 2. Click Eclipse IDE for ModbusToolbox
![Alt text](Img/image-6.png)

### 3. Click “New Application ” and it will automatically shell to Project Creator 2.0
![Alt text](Img/image7.png)
![Alt text](Img/image9.png)
### 4. Click “PSoC6 BSP s” and  following the below step
![Alt text](Img/image8.png)
### 5. Go to “Getting Started”
![Alt text](Img/image11.png)


## 3. “Hello World and LED Blinking” Programming.
### 1. Choose “Hello World” project and you can setting any name you want 
![Alt text](Img/image12.png)
### 2. Building and running project by click 
`Build Application` —> `[Project_Name] Program (KitProg3_MiniProg4)`

![Alt text](Img/image13.png)

