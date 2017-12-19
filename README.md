# GoLang-Sample-Codes
This is the solution directory for Hackerrank 30 Days of Code with GoLang.

How to Start with GoLang?
In order to start coding in GoLang, you need two things on your System (I am assuming, it is Windows).
1. SetUp of GoLang (Installed)
2. Editor to write the code

How to Install?

- Follow this link for the download of MSI - https://golang.org/doc/install?download=go1.9.2.windows-amd64.msi
- Once downloaded the file, click Run and Next..Next..Default settings will be just fine.
- The GO will create C:/Go directory in your system after installation (If ask for location while setting up, you can change it as per your system settings)
- Go to "bin" folder in Go directory (On my machine it is C:/Go/bin)
- Run any command prompt files to check the installation has been done (to verify that Go is installed)

Start Using Go?
- Create a directory at C:Go/Go_Workspace
- Create a file "FirstProgram.go" and type the below program

        package main

        import "fmt"

        func main(){
            fmt.Println("Hi, This is my first program in Go")
        }
 Now, open the Command Prompt on Windows
 - Move to cd C:/Go/Go_Workspace (Enter)
 - C:/Go/Go_Workspace>go run FirstProgram.go (Enter)
 
 You will see the output.
 
 Feel free to comment, in case of any doubt.
