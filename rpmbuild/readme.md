
1. build

python ../setup.py sdist --only-pyc

rpmbuild -ba ./python-setuptools.spec

2. note
Defualt will generate python2-setuptools packages 
If you want to generate python3-setuptools, you need 
to set fedora or set with_python3


