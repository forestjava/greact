# @greact/core

## Clojure Installation

Following the [clojure.org](https://clojure.org/guides/getting_started)
Ensure that the following dependencies are installed: `bash`, `curl`, `rlwrap`, and `Java`.

Use the `linux-install` script to download and run the install, which will create the executables `/usr/local/bin/clj`, `/usr/local/bin/clojure`, and the directory `/usr/local/lib/clojure`:
```
curl -O https://download.clojure.org/install/linux-install-1.10.1.763.sh
chmod +x linux-install-1.10.1.763.sh
sudo ./linux-install-1.10.1.763.sh
```

Check the installation
```
cljs (println "Hello, @greact/core")
```
You should see output like the following:
```
Clojure 1.9.0
user=>
```
