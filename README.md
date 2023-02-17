# Hi Welcome to the Documentation of i-Lib - Library Management System of RKMVCC

* [For Mobile User (Student)](#for-mobile-user-student)
* [For Mobile User (Admin)](#for-mobile-user-admin)
* [For Linux User (All)](#for-linux-user-all)
* [For Windows User (All)](#for-windows-user-all)

### For Mobile User (Student)

#### **Step 1**:

[Click Here](https://ilib.website) Or scan the QR code below with your mobile device with an active Internet connection.


![](https://cdn.jsdelivr.net/gh/Bijit-Mondal/iLib-Documentation@main/assets/20230108_180721_QR_Code.png)

#### **Step 2**:

Click on the three dots on your browser and press **Install app** button on the menu as shown below.


![](https://cdn.jsdelivr.net/gh/Bijit-Mondal/iLib-Documentation@main/assets/20230108_181832_Screenshot_2023-01-08-17-19-14-28.jpg)

#### **Step 3**:

Click on the **Install** button and wait for the installation process to finish.


![](https://cdn.jsdelivr.net/gh/Bijit-Mondal/iLib-Documentation@main/assets/20230108_182420_Screenshot_2023-01-08-17-19-22-94.jpg)

#### **Step 4**:

An app as above with name **iLib** will shown on your home screen.


![](assets/20230108_182646_Screenshot_2023-01-08-17-20-00-32.jpg)

#### **Step 5**:

Open the app, and go to the login section.


![](assets/20230108_183119_Screenshot_2023-01-08-17-20-11-91.jpg)

#### **Step 6**:

If you don't have an account on iLib, Press on the **Register for a new account** button.


![](assets/20230108_183505_Screenshot_2023-01-08-17-20-18-91.jpg)

#### **Step 7**:

Enter the proper details as required and upload a passport size photo or selfie of your own wearing the college uniform. **The photo size must be less than *350* kb**. The details will be checked before making you a premium user, so enter it carefully.


![](assets/20230108_184206_Screenshot_2023-01-08-18-41-39-78.jpg)

#### **Step 8**:

You will receive an e-mail with a verification link. Verify your email with it.


![](assets/20230108_194616_Screenshot_2023-01-08-17-24-11-49.jpg)

#### **Step 9**:

After clicking the link in the e-mail, your verfifcation status will be updated.


![](assets/20230108_202045_Screenshot_2023-01-08-17-25-09-27.jpg)

#### **Step 10:**

Logout from the application and login once again.


![](assets/20230108_202334_Screenshot_2023-01-08-17-25-21-09.jpg)

#### **Step 11:**

Go to library admin and ask him to update your premium status so that you will be able to request for books.


![](assets/20230108_202754_IMG_20230108_174107.jpg)

After updating the premium status, your 'Account Details' window will look like this.


![](assets/20230108_203211_IMG_20230108_174140.jpg)

#### **Step 12:**

Search and request for a book in the request window. You can borrow maximum of 2 books at a time. The books should be returned between 15 days.


![](assets/20230108_203327_Screenshot_2023-01-08-17-28-51-29.jpg)

#### **Step 13:**

For Returning a book you must go to library and ask admin to approve your return request.

### For Mobile User (Admin)

#### **Step 1:**

Step 1-10 are same as student user. You can go through it.

#### **Step 2:**

Asks the developer to make yourself admin.

#### **Making student premium:**

Go to student details section.


![](assets/20230108_210549_qwerty.jpg)

Click on the **Get details by email** button and enter the student email and search.


![](assets/20230108_210823_Screenshot_2023-01-08-17-34-22-68_e4424258c8b8649f6e67d283a50a2cbc.jpg)

Approve as premium user or delete the user.


![](assets/20230108_210925_Screenshot_2023-01-08-17-34-30-74_e4424258c8b8649f6e67d283a50a2cbc.jpg)

#### **Approve Pending Request**

Click on the **Load Pending Request** button and approve or decline student's borrow request.


![](assets/20230108_211231_Screenshot_2023-01-08-17-35-50-54_e4424258c8b8649f6e67d283a50a2cbc.jpg)

#### **Approve Return Request**

Click on the  **Load Return Request** button and approve return request. **If the user is late to return the book, fine charges button will glow**


![](assets/20230108_211538_Screenshot_2023-01-08-17-36-37-99_e4424258c8b8649f6e67d283a50a2cbc.jpg)

#### **Add a new book**

Click on the **Add a new book** button from menu and enter the details of the book, make sure each book has a ***unique*** ISBN number.


![](assets/20230108_211730_Screenshot_2023-01-08-17-32-34-09_e4424258c8b8649f6e67d283a50a2cbc.jpg)

#### **The image URL part**

Search for the book's front page image online and paste the link in the input area.


![](assets/20230108_211925_Screenshot_2023-01-08-17-33-29-97_e4424258c8b8649f6e67d283a50a2cbc.jpg)

#### **Upload book's pdf**

You can upload a book's pdf but then make sure the pdf is less than 1 MB in size.

> Enter the details of book properly for no furthur issue. And once again make sure each book has unique ISBN number and don't repeat a book twice.

### For Linux User (All)

#### **Step 1: Download**

> Ubuntu, Debian

First you need to download snap package manager on the machine.

```
$ sudo apt update
$ sudo apt install snapd
```

[Download the file](https://github.com/Bijit-Mondal/iLib-Documentation/releases)

Go to the downloaded directory and open terminal.

```
$ sudo snap install iLib_0.1.0_amd64.snap --dangerous
```

```
$ ilib
```

> Arch Linux

First you need to download snap package manager on the machine

```
$ git clone https://aur.archlinux.org/yay

$ cd yay

$ makepkg -si
$ yay -Sy snapd
```

[Download the file](https://github.com/Bijit-Mondal/iLib-Documentation/releases)
Go to the downloaded directory and open terminal.

```
$ sudo snap install iLib_0.1.0_amd64.snap --dangerous
```

```
$ ilib
```

#### **Step 2:**

Other steps are same as above.

### For Windows User (All)

#### ~~Step 1~~:

Sorry windows users, I haven't developed iLib for windows, nor do I want to. If you really want desktop like experience on windows download the Web App :)
