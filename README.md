# BachelorThesis : Detection of Non-Inclusive Language in RTL News Articles

This thesis aimed to create a model that can detect non-inclusive language in RTL news articles. The associated model can be found in this repository.

Due to privacy concerns and data breaches, the data is not included in this repository.

## Installations and imports
!pip install typing-extensions
!pip install openai==1.38.0

import os
import pandas as pd
import ast
import re
import openai
import pprint
import random
import pyspark.sql.functions as F
import numpy as np
from openai import OpenAI

from tenacity import (
    retry,
    stop_after_attempt,
    wait_random_exponential,
)
