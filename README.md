# CC-Botnet-in-Python
C&#38;C Botnet written in Python

<h2>Description</h2>
Simple botnet written in Python using fabric. 
<p>
The author is not responsible for the use of this code.

<h2>Hosts</h2>
It is possible to load hosts from a file _hosts.txt_ included in the main directory of the project.
The default format for this file is:
<xmp>username@host:port password</xmp>

If the port is not indicated, port 22 is used:
<xmp>username@host password</xmp>
SSH connection is the default authentication way, so if the host knows the public key of the user, it is not necessary to indicate the password:
<xmp>username@host</xmp>

<h2>Usage</h2>
To start the application, simply download the repository
<xmp>https://github.com/marcorosa/CC-Botnet-in-Python
cd CC-Botnet-in-Python
</xmp>
Create the _hosts.txt_ file (optional, see above), and run the start script
<xmp>
python start.py
</xmp>

