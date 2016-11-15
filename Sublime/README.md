Sublime text 3

[Sublime](http://www.cnblogs.com/Rising/p/3741116.html)
[sublime text 3 ftp](https://my.oschina.net/surjur/blog/392590)

Install Plug-in

  Ctrl + `
  
  ```
  import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
  ```
