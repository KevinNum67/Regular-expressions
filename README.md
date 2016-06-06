# Regular-expressions
Reminder about regular expressions usage
RE                                                             Match
^abc.*                                                     abcdefg/abcbe/abc
0?(13|14|15|18)[0-9]{9}                                    telephone number
\d{6} or [0-9]{6}                                          zip code
[1-9]([0-9]{5,11})                                         QQ number
\d{17}[\d|x]|\d{15}                                        Identity card number
\s                                                         blank line
\w[-\w.+]*@([A-Za-z0-9][-A-Za-z0-9]+\.)+[A-Za-z]{2,14}     Email address
^((https|http|ftp|rtsp|mms)?:\/\/)[^\s]+                   web URL

