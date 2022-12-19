# i3genabar

A simple shell script that outputs status\_commands according to the i3bar protocol
<br>
__Important!!__: This script is a template and some features are suited for my machine 

## Requirements

- dunst
- cal
- pamixer

## Features

- datetime + calendar notification
- keyboard layout 
- private ip
- disk usage
- volume 
- battery
- wifi signal strength

## How to install

1. Install the script

```sh
$ sudo ./install.sh
```

2. Include the script in your `i3.conf`:

```bash:
bar {
	# some other config
    status_command i3genabar
    # some other config
}

```



## Examples

- Running the calendar example![example1](https://user-images.githubusercontent.com/59848681/208462927-e656f218-3fdb-4997-92ef-eaf229dcd397.png)

- Example of disk usage![example2](https://user-images.githubusercontent.com/59848681/208462931-b7aa60e4-a562-4ace-8d6b-b0cb309b3b9f.png)
