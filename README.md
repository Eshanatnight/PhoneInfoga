# An OSINT Investigator For Phone Numbers

    International Contacts Supported
    CLI Based

</br>

## Usage Details

    1. Use of A VPN or Tor is Preffered before use for better security of users information
    [optional]

</br>

    2. Run over Terminal
    [ Do Not Directly run the Executable]

</br>

---

## Using The Executable

```sh
    git clone "https://github.com/Eshanatnight/PhoneInfoga"
```

```sh
    cd PhoneInfoga

    Or

    dir PhoneInfoga
```

```sh
    phoneinfoga.exe
```

</br>

---

## Available Commands

    1. help        Help about any command
    2. scan        Scan a phone number
    3. serve       Serve web client
    4. version     Print current version of the tool

</br>

---

### Flags

    1. scan
                -h, --help            help for scan
                -n, --number-string   The phone number to scan (E164 or international format)



    2. serve
                -h, --help        help for serve
                --no-client   Disable web client (REST API only)
                -p, --port int    HTTP port (default 5000)

</br>

---

## Example

```sh
    phoneinfoga scan -n <number>
```

</br>

---

### Based on :



<p align="center">
    sundowndev/PhoneInfoga
    </br>
    <a href="https://github.com/sundowndev/PhoneInfoga" title="sundowndev/PhoneInfoga">
        <img src="https://i.imgur.com/LtUGnF3.png" width=500 />
    </a>
</p>

## About

PhoneInfoga is one of the most advanced tools to scan international phone numbers using only free resources. It allows you to first gather standard information such as country, area, carrier and line type on any international phone number. Then search for footprints on search engines to try to find the VoIP provider or identify the owner.

