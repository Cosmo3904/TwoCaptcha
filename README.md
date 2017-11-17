# TwoCaptcha
## Easy 2captcha Python Wrapper

## Usage:

from twocaptcha import TwoCaptcha



s = TwoCaptcha(API_KEY, SITEKEY, URL)


token = s.solve()


if token == 'ERROR_ZERO_BALANCE':

  print('0 BALANCE')
  
else:

  print('Valid Recaptcha Token : ' + token)
