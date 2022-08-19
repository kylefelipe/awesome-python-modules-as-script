# Awesome Python modules as script

Catalogue of useful python modules that run as script.

## Requirements:
* Python 3

## How to use?

You have to type: `python -m <name>`.

You can access help for some modules through: `python -m <name> --help` or `python -m <name> -h`.

Standard Library
----------------

| Name             | Description                                       | Example                                         |
| :------------    |:------------------------------------------------- |:---------------------------------------------   |
| ast              | Parse abstract syntax tree for a Python module    | python -m ast myfile.py                         |
| asyncio          | Asyncio REPL                                      | python -m asyncio                               |
| antigravity      | Open browser with http://xkcd.com/353             | python -m antigravity                           |
| base64           | Encode and decode base64                          | echo 'message' \| python -m base64 -e           |
| cProfile         | Profiling your code                               | python -m cProfile module.py                    |
| calendar         | Pretty print a calendar                           | python -m calendar                              |
| code             | Closely emulate the interactive Python interpreter| python -m code                                  |
| compileall       | Compile Python source files in a directory tree   | python -m compileall                            |
| dis              | Print bytecode generated by a file                | python -m dis some_module.py                    |
| doctest          | Run doctests in a file                            | python -m doctest myfile.py                     |
| encodings.rot_13 | ROT-13 encoder/decoder                            | echo 'message' \| python -m encodings.rot_13    |
| ensurepip        | Bootstrap pip if it was skipped or uninstalled    | python -m ensurepip                             |
| filecmp          | Compare two directories content                   | python -m filecmp dir_a dir_b                   |
| ftplib           | Simple ftp client                                 | python -m ftplib [host]                         |
| gzip             | Compress and decompress files                     | python -m gzip [file]                           |
| http.server      | Simple HTTP Server                                | python -m http.server 5000                      |
| idlelib          | Launch IDLE prompt                                | python -m idlelib                               |
| inspect          | Inspect a object.                                 | python -m inspect "collections:OrderedDict"     |
| json.tool        | Validate and pretty-print JSON                    | echo '{ 1.2:3.4}' \| python -m json.tool        |
| lib2to3          | Automated Python 2 to 3 code translation          | python -m lib2to3 -w [python file]              |
| locale           | Show O.S Locale information                       | python -m locale                                |
| mimetypes        | MIME type/extension database                      | python -m mimetypes -e application/json         |
| pdb              | Automatic post-mortem debugging                   | python -m pdb myscript.py                       |
| pickle           | Display contents of the pickle files              | python -m pickle [pickle files]                 |
| pip              | Python package manager                            | python -m pip install requests                  |
| platform         | Show current platform                             | python -m platform                              |
| poplib           | List POP3 mailbox                                 | python -m poplib [server] [username] [password] |
| profile          | Profiling your code                               | python -m profile some_module.py                |
| pstats           | Print profiling statistics                        | python -m pstats  [file generated by profile]   |
| pyclbr           | Extract classes and methods from a module         | python -m pyclbr [module]                       |
| pydoc            | Consult the documentation                         | python -m pydoc -b                              |
| quopri           | Encode and decode MIME quoted-printable data      | echo 'message' \| python -m quopri              |
| site             | List your current path                            | python -m site                                  |
| smtplib          | Send a mail message(to localhost)                 | python -m smtplib                               |
| sysconfig        | Shows paths and Python internal variables         | python -m sysconfig                             |
| tarfile          | Read and write tar files                          | python -m tarfile -e myfile.tar                 |
| telnetlib        | Telnet client                                     | python -m telnetlib  towel.blinkenlights.nl     |
| this             | Zen of python                                     | python -m this                                  |
| timeit           | Measuring execution time of small code snippets   | python -m timeit 'sorted(range(100))'           |
| tokenize         | Show how python tokenize a file                   | python -m tokenize some_module.py               |
| turtledemo       | Educational demos for turtle module               | python -m turtledemo                            |
| unittest         | Run tests using unittest                          | python -m unittest .                            |
| uu               | Encode and decode uuencode files                  | echo 'message' \| python -m uu                  |
| venv             | Create a virtual enviroment                       | python -m venv myproject                        |
| webbrowser       | Open a web browser                                | python -m webbrowser http://httpbin.org         |
| zipapp           | Create an executable ZIP file from Python code    | python -m zipapp mydir -m "module:main"         |
| zipfile          | Zip operations like create, test or extract       | python -m zipfile -e zipfile.zip target         |


Third party packages
--------------------

They can be installed through: `python -m pip install [module name]`.


| Name          | Description                                     |Example                               |
|:------------- |:----------------------------------------------- |:-------------------------------------|
| black         | The uncompromising code formatter               | python -m black .                    |
| flake8        | Tool For Style Guide Enforcement                | python -m flake8 path/to/code/       |
| pytest        | Run tests using pytest                          | python -m pytest -s path/to/tests/   |


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
