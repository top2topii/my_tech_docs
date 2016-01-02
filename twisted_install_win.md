

## Install Twisted 15.5.0 for python 2.7 64bit

'''

    Windows
    
    Twisted 15.5.0 for Python 2.7 64 bits (​whl)
    ​Zope.Interface (required)
    ​PyWin32 (required)
    ​PyOpenSSL (needed for SSL
'''

###1. Environment Variable

  - Add C:\Python27;C:\Python27\Scripts

###2. Reopen CMD Windows 

###3. pip install zope.interface

###4. Download PyWin

  - https://pypi.python.org/pypi/pypiwin32
  - Click to download: pypiwin32-219-cp27-none-win_amd64.whl (md5)
  - python -m pip install pypiwin32-219-cp27-none-win_amd64.whl

###5. Download PyOpenSSL

  - https://pypi.python.org/pypi/pyOpenSSL
  - Click to download: pyOpenSSL-0.15.1-py2.py3-none-any.whl
  - python -m pip install pyOpenSSL-0.15.1-py2.py3-none-any.whl

###6. Download Twisted
  - http://twistedmatrix.com/trac/wiki/Downloads
  - Twisted 15.5.0 for Python 2.7 64bits download
  - python -m pip install Twisted-15.5.0-cp27-none-win_amd64.whl




###99. 곁가지

  - wget: http://nebm.ist.utl.pt/~glopes/wget/ 에서 64bit용 받아서 설치.

###100. 경험으로 얻은 주의사항

  - cygwin에서 Windows python을 개발하지 말자. 어떤 python이 실행되는지 헷갈린다.
  - CMD 창이나 PyCharm을 사용토록 한다.
