# `nano-nocode`

Syntax highlighting for the [`nocode` language](https://github.com/kelseyhightower/nocode) in the `nano` code editor.

## Installation

Run:

```sh
git clone https://github.com/Yash-Singh1/nano-nocode.git
cd nano-nocode/
```

Then run:

### Ubuntu/Debian

```sh
sudo cp nocode.nanorc /usr/share/nano/
```

### Mac

```sh
sudo -i
mkdir /usr/local/share/nano/
echo 'include "/usr/share/nano/*.nanorc"' >> /etc/nanorc
cp nocode.nanorc /usr/local/share/nano/
```

### Windows

<!-- markdownlint-disable-next-line MD036 -->
**Note: Remember to run as administrator**

```sh
cp nocode.nanorc /usr/share/nano/
```

## Usage

Creating and editing a `.no` file should give errors.
