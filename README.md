# First-home-work-YouZhen.Duan
If 1, 2 and 3 are done, create your first GitLab repo containing a README.md file. It will briefly describe the steps you followed to set your environment up. e.g. the OS, the command used, the problems encountered, how you solved them, etc...

1.Python download and installation

1.1.Uninstalling an Existing Python Installation

（1）Delete the remaining Python folder:
Finding and deleting leftover python files with everything
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/454e9b63-388c-4390-9215-ea1913777f5a)

（2）Cleaning up system environment variables

.Search for "Environment Variables" in the Start menu and open "Edit System Environment Variables".

.Click the "Environment Variables" button.

.Find the variable called "Path" in the "System Variables" section and double-click it.

.In the "Path" variable, find any Python-related entries (e.g., directories starting with or containing C:\Python) and delete them one by one. Click "OK" to save the changes.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/6cb9687a-e276-4808-95de-db2b7511e6f7)

1.2.Installing a new python environment.

(1)Go to the python website, select the version and download the windows 64-bit installer.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/35b5115e-78cb-49bb-a9d6-cec069982a86)

(2)Run the installer to complete the installation process.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/cd74879d-bbc4-40d4-b733-3663ec875a42)

1.3IVerify that python was installed successfully in a command prompt window.

（1）Type "python" in a command prompt window.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/886f1dea-e28e-48e7-a299-a805291b7fb8)

2.Installation and configuration of the pycharm environment.

2.1.Go to pycharm official website to download pycharm.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/ce505791-f96a-4a7e-9eb1-e5e8bd167a41)

2.2.New project using python as base interpreter.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/8c92ac63-504c-4af5-9037-59b565d262fe)

2.3.Type "hello world!" and run.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/70c667c2-17b6-4b3a-8864-23dcb0706fb6)
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/9d93e251-fe38-495e-99ef-e3c7e89f548b)

3.Installing Django using the pip tool.

3.1.Check if pip version is available.

(1)Type "pip -V" in a command prompt window.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/591eba79-3975-45f0-8158-5c519602d19a)

(2)At this point, the pip version is found to be low, so type "pip install --upgrade pip" to upgrade it.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/3acfb0dc-5367-4141-ae5e-598c6262d27e)

Question 1 arises at this point: pip download timeout.

Solution: Use mirror resources to download, mirror resources from China's computer forums.

The relevant code is as follows:
python -m pip install --upgrade pip -i https://pypi.douban.com/simple
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/1c408ca8-4452-4d85-8834-58c607e66f5a)

(3)Check pip version again after successful installation.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/9de0c81b-eb1e-4f60-82c5-b4c9c4d2b42d)

New version installed successfully!


3.2.Installing the Django environment using the newly installed pip tool.

Enter the installation code "pip install django" in a command prompt window.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/68755704-0c2d-4839-8edc-ce4e0743d8c0)

Question 2 arises at this point: Still Django download timeout.

Solution: Or use the mirror resources to download, the mirror resources from the famous Chinese company Alibaba's Aliyun server.

The relevant code is as follows:
pip install django -i https://mirrors.aliyun.com/pypi/simple/
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/b06905a3-fd80-4a80-adab-5d350bf73833)

3.3.Installation Verification.

Type "pip list" in a command prompt window.
![image](https://github.com/YorkDuan/First-home-work-YouZhen.Duan/assets/156828673/b63209d1-b030-43bc-95a3-04e7034dc157)

The installation was successful!

At this point, the python environment is configured.























