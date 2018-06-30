# -v.9
ไฟล์ได้โทเค็นแล้ว
# -*- coding: utf-8 -*-

import LINETCR
#import wikipedia
from LINETCR.lib.curve.ttypes import *
#from ASUL.lib.curve.ttypes import *
from datetime import datetime
# https://kaijento.github.io/2017/05/19/web-scraping-youtube.com/
from bs4 import BeautifulSoup
from threading import Thread
from googletrans import Translator
from gtts import gTTS
import time,random,sys,json,codecs,threading,glob,urllib,urllib2,urllib3,re,ast,os,subprocess,requests,tempfile                                                                       cl =LINETCR.LINE()
#cl.login(qr=True)
cl.login(token='u08e792afc65a2c6b7d54ea8ff5958176')
cl.loginResult()
 
