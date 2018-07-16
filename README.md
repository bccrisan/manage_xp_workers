### Using the available suport via Servic Now, we are able to do reboot without the need of a web browser.

#### Before using the script you will need to install Java & Java Web Service by doing:
`sudo apt install default-jre icedtea-netx`


In the folder `workers/` you are going to find a file for each server, and a few modifications are required to make those work.

Since these machines are password protected, opening each file in text editor, you'll observe at the end of the files, a few `username` and `password` fields, replace those with the known username and password and should be good to go.

### *Attention*: After the first open up, the passwords are saved in cache, and in the files, the default username and password is going to be something else *(automatically replaced)*.


#### Use case:
1. Terminal:

    `javaws name_of_the_server.jnlp`


2. GUI:

    Open file via Java Web Service *(double click or right click and open with Java Web Service)**

*If it doesn't show up as an `open-with` option, probably `icedtea-netx` is **not** installed.
