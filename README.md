# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## REG NO:212222230028
## NAME: DEEPIKA S
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROCEDURE:
StegExpose and File Signature Analysis Commands

# Step 1: Download Image and Create Secret Message File
• Download a .jpeg image  from a trusted website or use own image.

![1img](https://github.com/user-attachments/assets/e5bf7817-4a9e-40cf-8da3-4f27fad7eb9b)


• Create a text file named secret with a confidential message:

![2img](https://github.com/user-attachments/assets/b564202d-aaab-4b4d-9582-2ad27175a232)


# Step 2: Install and Verify Steghide Tool
• To install Steghide on Kali linux,run:

• Confirm the installation by checking its version:

![image](https://github.com/user-attachments/assets/a10a04a2-6266-4a5c-98e5-e4e331318e81)

# Step 3: Embed the Secret Message into the Image
• Use the following command to embed secret into praveen.jpeg:

![image](https://github.com/user-attachments/assets/0b461cbe-10e5-4f1f-a272-240f39ed531d)

# Step 4: Delete the Original Secret File
• After embedding, delete the plaintext file:

![image](https://github.com/user-attachments/assets/a3bb37c5-8e86-4b53-a869-2a26ca227244)


## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

# Step 1: Extract the Embedded Secret from the Image

![image](https://github.com/user-attachments/assets/4c39d9c7-92a9-4081-b40d-ea5540e94c49)

• To retrieve the hidden file:
• Enter the same passphrase used during embedding.



# Step 2: Verify the Extracted Message
• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

# Step 3: Retrieve Information About the Embedded Data
• To gather details about embedded content in the image:

![image](https://github.com/user-attachments/assets/9a499ab3-50fd-4a9d-a08f-5a01eca456b8)

• This will display file type, size, and whether data is embedded.
## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
