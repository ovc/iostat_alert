# Iostat Alert for OS Solaris



### Installation

1. Download and install
   ```sh
   curl -ks https://raw.githubusercontent.com/ovc/iostat_alert/main/(uname -o)/install | sh
   ```
3. Source your .profile
   ```sh
   source ~/.profile
   ```



<!-- USAGE EXAMPLES -->
## Usage

* Check once
   ```sh
   iostat_alert check
   ```
* Test mail
   ```sh
   iostat_alert testmail
   ```
* Install as service
   ```sh
   iostat_alert setup
   ```
   This will add a string to your cron daemon
   ```sh
   # 10 0 * * * /root/bin/iostat_alert stop >/dev/null 2>&1; /root/bin/iostat_alert start >/dev/null 2>&1
   ```
   


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- SEE ALSO -->
## See also

sendEmail: [https://github.com/mogaal/sendemail](https://github.com/mogaal/sendemail)



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/ovc/iostat_alert](https://github.com/ovc/iostat_alert)
