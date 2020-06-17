# Revised instaloader package
Original package repo:
https://github.com/instaloader/instaloader

#### Modified:
* Add the ProxyInvalidException class in exceptions.py
* Modifed Exception handling behavior of TooManyRequestsException, ProxyInvalidException: Directly raise the exception to the caller instead of waiting and retrying
