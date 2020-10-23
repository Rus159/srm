# SafeRM
> bash script that does not immediately delete files, but first moves them to trash

## Installation
Create a bin folder in your home directory (~/bin), clone the repository and move the srm file to the created directory, then add the path to ~/bin to ~/.bash_profile:
```sh
mkdir ~/bin
git clone https://github.com/Rus159/srm
mv srm/srm ~/bin
echo 'export PATH="${PATH}:~/bin"' >> ~/.bash_profile
```
...and reconnect to the server.

## Usage example

```sh
srm FILENAME
```

## Meta

Semen Zabelin – [@szabelin159](https://vk.com/szabelin159) – zabelin.tollyatti@yandex.ru

[https://github.com/Rus159/](https://github.com/Rus159/)

## Contributing

1. Fork it (<https://github.com/Rus159/srm/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
