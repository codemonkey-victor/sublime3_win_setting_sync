
##First, install PackageControl##
Open Console, keys: Ctrl + ~
Enter:
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

Note: If you want auto install packages , you must be install Package Control first!


##Emmet install##
When install Emmet plugin you need install PyV8 package.
Try to manually install PyV8 from
https://github.com/emmetio/pyv8-binaries
eg windows:
\Sublime Text 3\Installed Packages\PyV8\__DOWNLOAD_FILE__

