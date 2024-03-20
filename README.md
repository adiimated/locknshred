# Lock N Shred

This shell script provides a simple way to encrypt and decrypt files using OpenSSL from the command line. It supports AES-256-CBC encryption and includes an optional feature for securely deleting the original file after encryption.

## Requirements

* OpenSSL: We use OpenSSL for encryption, decryption, and deletion. Ensure OpenSSL is installed and accessible from your command line. You can do this by entering `openssl version` in your terminal. If you get an version number, you are good to go, otherwise you will have to install it.
* Bash: The scripts are written for Bash and should run on any Unix-like operating system, including Linux and macOS.

## Usage

1. Clone or download the utility's scripts to your local machine.
```
git clone https://github.com/adiimated/locknshred.git
```

2. Change the permissions of the scripts to make them executable. Run the following command:
```
chmod +x encrypt.sh decrypt.sh
```

3. To encrypt a file, use the following syntax:
```
./encrypt.sh <filename> <password> [delete]
```
`[delete]`: This is an optional argument. Include it if you want to securely delete the original file after encryption.

4. To decrypt a file, use the following syntax:
```
./decrypt.sh <filename> <password>
```

## Example Screenshot:

![](https://github.com/adiimated/locknshred/blob/main/execution.png)

Contributions are welcome. Fork the repository and submit a pull request with your enhancements/fixes.

