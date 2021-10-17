## C++ VS Code Config
Install C++ extension : press `ctrl+p` and paste and enter, `ext install ms-vscode.cpptools`

 **to run `helloworld.cpp` and make executable file in terminal**
```shell
g++ -o helloworld helloworld.cpp
//or
g++ -o helloworld.out helloworld.cpp
```
**to run executable file**
```shell
g++ helloworld
or 
g++ helloworld.out
```

## if Config setup file exist then
#### To build - ctrl+shift+b
press `ctrl+shift+b` in vs code. it will  build a executable file. behind the scene it run this command `g++ -o hello.out hello.cpp`
 - for this config are in **tasks.json** file

#### To Run and Debug - ctrl+f5
to run press `ctrl+f5`. it will run `./hello.out` in terminal 
 - this config are in **launch.json**

 #### more control in **c_cpp_properties.json**

 Thanks.
