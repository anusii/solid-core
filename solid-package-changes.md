
# Solid package changes

**Description**
We currently have three different solid based flutter packages but they are incomplete and missing some of the functionalities that we have recently developed. 
So we need to get these packages up-to-date and clean up legacy functionalities. 

## Solid-auth
- This package is mostly complete. The only thing we have to do is look for any dart metric issues, formatting issues and also clean up the code so that the codebase is divided between multiple smaller files (if required).
- Also add more comments to the functions if needed.

## Solid-encrypt
- This package needs more work. Currently this package only allows the encryption of data (files) using the master key. But we now use different framework for data encryption. This package needs to be changed accordingly. Changes required are as follows:
- Storing of master key using Flutter secure storage
- Creating session/random AES key for each file a user encrypts
- Creating public/private key pair for sharing encrypted data. Private key needs to be encrypted using the master key
- Creating all the necessary file and folder structures required for data encryption and sharing
- Sharing of encrypted data
- Revoke access to encrypted data
- A way to track all the encrypted data and shared encrypted data
- Change master key
- Have the option to encrypt either individual files or individual triples inside the files 

*Note: Almost all of the above functionalities are already implemented in Clinic, Indi, and Podnotes apps. All we have to do is reuse those functionalities in this package.*

## RDFlib
- The current version we have of this package contain only a limited number of functionalities. We need to improve and add new functionalities to this package so it will work on other use cases as well.
- Ability to read ACL files
- Ability to query a graph
- Ability to add content to a file in a POD
- Ability to change/modify/delete file content stored in a POD
- A good approach would be to compare the functionalities of our package with Python RDFlib package. Our goal should be to modify the package so it will have all the important functions of Python RDFlib package

## Solid-basic
- This is a complete new package which will contain all the basic functionalities we usually use across projects.
- Some example functionalities could be:
	- Creating folders and files inside a pod along with their corresponding ACL files
	- Reading files inside a POD
	- Run SPARQL queries to delete/update/add content in/to files inside a POD
	- Add/edit/remove permissions from ACL files
  
*Note: When implementing these functionalities this package might need the above packages as well*