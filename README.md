# Socket Programming
### Implementation of a simplified FTP server and FTP client.


## Collaborators
* Alexis Vu (alexislayvu@csu.fullerton.edu)
* Christian Mendez (christianmendez@csu.fullerton.edu)
* Gilbert Espino Solis (Gil.espino18@gmail.com)


## Usage
1) Execute `server.py` in a Terminal window with the following command, replacing `<PORTNUMBER>` with your desired port number: `python server.py <PORTNUMBER>`.
    - Example: `python server.py 1234`
2) In a separate Terminal window, run `client.py` using the following command, and again, replace `<PORTNUMBER>` with the same port number as before: `python client.py localhost <PORTNUMBER>`.
    - Example: `python client.py localhost 1234`
3) Upon connecting to the server, the client prints out `ftp>`, allowing you to execute the following commands:
    - `get <filename>`: Downloads file `<filename>` from the server.
        - Example: `ftp> get file.txt`
    - `put <filename>`: Uploads file `<filename>` to the server.
        - Example: `ftp> put file.txt`
    - `ls`: Lists files on the server.
        - Example: `ftp> ls`
    - `quit`: Disconnects from the server and exits the client.
        - Example: `ftp> quit`
4) Once you're finished, use the `quit` command to exit the program.


## Example
<img width="1440" alt="Screenshot 2024-02-15 at 9 24 21 PM" src="https://github.com/alexislayvu/Socket-Programming/assets/54639928/3835c3cc-041a-4744-8974-e50086ec5f61">
