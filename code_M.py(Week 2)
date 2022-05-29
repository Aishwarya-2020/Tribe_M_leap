#!/usr/bin/env python
# coding: utf-8
# In[1]:
import pandas as pd
import seaborn as sns
sns.set(color_codes=True)
weather=pd.read_csv('dine.csv')
# In[2]:
weather.head()
# In[3]:
weather.info()
# In[4]:
sns.barplot(weather['Location'],weather['Budget'])
# In[5]:
sns.distplot(weather['Overall Rating'])
# In[7]:
sns.jointplot(weather['Marital Status'],weather['Budget'])
# In[10]:
sns.jointplot(weather['Area code'],weather['Budget'], kind="hex")
# In[11]:
sns.jointplot(weather['Area code'],weather['Budget'], kind="kde")
# In[12]:
sns.countplot(weather['Marital Status'])
# In[13]:
sns.countplot(weather['Gender'])
# In[14]:
sns.countplot(weather['Gender'], weather['Marital Status'])
# In[15]:
sns.countplot(weather['Location'])
# In[16]:
sns.countplot(weather['YOB'])
# In[17]:
sns.countplot(weather['Activity'])
# In[18]:
sns.jointplot(weather['Activity'],weather['Budget'])
# In[19]:
sns.jointplot(weather['Cuisines'],weather['Budget'])
# In[20]:
sns.countplot(weather['Cuisines'])
# In[21]:
sns.countplot(weather['Overall Rating'])
# In[22]:
sns.countplot(weather['Smoker'])
# In[23]:
sns.countplot(weather['Alcohol'])
# In[24]:
sns.countplot(weather['Budget'])
# In[25]:
sns.countplot(weather['Food Rating'])
# In[26]:
sns.stripplot(weather['Activity'],weather['Overall Rating'], jitter=True)
# In[27]:
sns.jointplot(weather['Area code'],weather['Budget'], kind="kde")
# In[28]:
sns.pairplot(weather[['Gender','Budget','Overall Rating']])
# In[29]:
sns.pointplot(weather['Cuisines'],weather['Overall Rating'], hue=weather['Budget'])
# In[30]:
sns.lmplot(x="Budget",y="Overall Rating",data=weather)
