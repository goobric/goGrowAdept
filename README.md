# goGrowAdept

## Where does Golang reside on the computer?

### Windows File System (fs)
*   C:
    *   -Go <-- where Golang is installed, GOROOT should point to here
    *   -goworkspace  <-- where the files that are created exist, GOPATH should point to here
        * -bin
        * -pkg
        * -src

### Linux File System (fs)
* -/
    *   -usr
        *   local
            * -go  <-- where Golang is installed, GOROOT should point to here
        *   home
            * -goworkspace <-- where the files that are created exist, GOPATH should point to here
                * -bin
                * -src
                * -pkg
