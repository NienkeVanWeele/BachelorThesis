# BachelorThesis : Detection of Non-Inclusive Language in RTL News Articles

This thesis aimed to create a model that can detect non-inclusive language in RTL news articles. The associated model can be found in this repository.

Due to privacy concerns and data breaches, the data is not included in this repository.

## Installations and imports
!pip install typing-extensions
!pip install openai==1.38.0

import os <br />
import pandas as pd <br />
import ast <br />
import re <br />
import openai <br />
import pprint <br />
import random <br />
import pyspark.sql.functions as F <br />
import numpy as np <br />
from openai import OpenAI <br />

from tenacity import ( <br />
    retry, <br />
    stop_after_attempt, <br />
    wait_random_exponential, <br />
)

## Author
Nienke van Weele <br />
s1067463
