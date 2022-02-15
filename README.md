# ☠️ Wordpress DoSer
Wordpress and Drupal XMLRPC Attack (DoS). XMLRPC is older than WordPress itself. This system was introduced to WordPress to fight the slow internet connection dilemma by helping the users write new posts offline and then uploaded them to the server. The ability to connect WordPress remotely with other applications was only possible with the `xmlrpc.php` file. XMLRPC parsing is vulnerable to a XML based denial of service. **Works on all WordPress sites where xmlrpc.php file manipulation is allowed**

------

# ⚠️ Warining
The author assumes no responsibility for the illegal use of the information provided (the script is educational in nature and its unauthorized implementation is punishable by law)

-----

## ✨ Usage
First of all you need to clone this script and install requirements
```bash
$ git clone https://github.com/Kuduxaaa/wp-doser
$ cd wp-doser
$ pip3 install -r requirements.txt
```

⚙️ Arguments for use and instructions

```python3
usage: exploit.py [-h] [-u URL] [-i IP] [-v VIRTUALHOST] [-m MULTIPLE]
                 [-t THREADS] [-xp XMLPATH]

optional arguments:

  -h, --help            show this help message and exit
  -u, --url             Target website URL
  -i, --ip              Target website IP Address
  -v, --virtualhost     Target website hostname (if enter only ip)
  -m, --multiple        Repeat several times
  -t, --threads         Threads count
  -xp, --xmlpath        XMLRPC path
```

## 💖 Useful links
 - [What is XMLRPC and How You Can Stop Hackers From Using It To Hurt Your Online Business](https://servebolt.com/articles/what-is-xmlrpc-and-how-you-can-stop-hackers-from-using-it-to-hurt-your-online-business/)
 - [ Wordpress XMLRPC DoS ](https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos/)
