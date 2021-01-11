# Hello World in C#

## Pre-requisite
Following Compiler need to be installed .!
---
Run Following Command in your Terminal
```bash
    sudo apt-get update
```
```bash
    sudo apt install mono-complete
```
```bash
    sudo apt install mono-mcs
```
## After Installation

Create Your hello-world.cs file and add the following code

```cs
namespace HelloWorld
{
    class Hello {         
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello World!");
        }
    }
}
```
## Compile

Compile your hello-world.cs file by following command

```bash
    mcs hello-world.cs
```
Now your hello-world.cs file will be compilled and a hello-world.exe will be generated for the same

Run your hello-world.exe by following command

```bash
    mono hello-world.exe
```