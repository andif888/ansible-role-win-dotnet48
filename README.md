# ansible-role-win-dotnet48

Ansible Role to install .Net 4.8 on Windows

## Table of content

- [Default Variables](#default-variables)
  - [dotnet48_download_url](#dotnet48_download_url)
  - [dotnet48_download_validate_certs](#dotnet48_download_validate_certs)
  - [dotnet48_install_file](#dotnet48_install_file)
  - [dotnet48_optimize_assemblies](#dotnet48_optimize_assemblies)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### dotnet48_download_url

Download URL of the package.

#### Default value

```YAML
dotnet48_download_url: http://go.microsoft.com/fwlink/?LinkId=2085155
```

### dotnet48_download_validate_certs

Validate SSL cert when downloading.

#### Default value

```YAML
dotnet48_download_validate_certs: yes
```

### dotnet48_install_file

Install package file name.

#### Default value

```YAML
dotnet48_install_file: ndp48-web.exe
```

### dotnet48_optimize_assemblies

Run ngen.exe after install to optimize assemblies.

#### Default value

```YAML
dotnet48_optimize_assemblies: true
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
