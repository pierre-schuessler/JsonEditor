# JSON Editor

The JSON Viewer / Editor allows the user to open any json files on your computer or from a url via the _source_ url parameter and have it displayed in a nice, intuitive manner. From there, the user can edit it easely and download the updated version.
The current version supports all official JSON data types: null, strings, booleans, integers, arrays and objects. The user can change any data types. The programm will try to transfer data as much as possible between types to prevent accidental data deletions.

Do not use it to edit important data. It may have unexpected behavior.

---

## Usage

Download the files and open the _index.html_ file in your favourite web browser.

Make sure it can access the other files (js and css). For this, you may want to start a http or https server.
Here is an example for python (run this command in the directory in which you saved the programm files):
```bash
py -m http.server
```
Then open :
```
http://localhost:8000/
```
