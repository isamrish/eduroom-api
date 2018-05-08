[![Build Status](https://travis-ci.org/eduroom/eduroom-api.svg?branch=master)](https://travis-ci.org/eduroom/eduroom-api

#### License ####

Every code patch accepted in taiga codebase is licensed under [AGPL v3.0](http://www.gnu.org/licenses/agpl-3.0.html). You must be careful to not include any code that can not be licensed under this license.

Please read carefully [our license](https://github.com/taigaio/taiga-back/blob/master/LICENSE) and ask us if you have any questions.


#### Translation ####

We are ready now to accept your help translating Taiga. It's easy (and fun!) just access our team of translators with the link below, set up an account in Transifex and start contributing. Join us to make sure your language is covered! **[Help Taiga to translate content](https://www.transifex.com/taiga-agile-llc/taiga-back/ "Help Taiga to trasnlatecontent")**

## Setup development environment ##

Just execute these commands in your virtualenv(wrapper):

```
pip install -r requirements.txt
python manage.py migrate --noinput
python manage.py loaddata initial_user
python manage.py loaddata initial_project_templates
python manage.py sample_data
```

**IMPORTANT: only runs with python 3.4+**

Initial auth data: admin/123123

