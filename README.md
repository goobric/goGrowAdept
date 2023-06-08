# goGrowAdept

## Where does Golang reside on the computer?

### Windows File System (fs)
*   C:
    *   -Go <-- where Golang is installed, GOROOT should point to here
    *   -goworkspace  <-- where the files that are created exist, *GOPATH* should point to this location
        * -bin
        * -pkg
        * -src

### Linux File System (fs)
* -/
    *   -usr
        *   local
            * -go  <-- where Golang is installed, GOROOT should point to here
        *   home
            * -goworkspace <-- where the files that are created exist, *GOPATH* should point to this location
                * -bin
                * -src
                * -pkg

### To check the location on your system, use the following command in the terminal:
*   go env

