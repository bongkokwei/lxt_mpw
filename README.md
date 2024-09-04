Install the required packages

```bash
pip install -r requirements.txt
```

Please use python 3.11, I've tried 3.10 (lnoi400 package will not install) and 3.12 (compatibilty issues with Klayout)

Open up bash terminal as admin, navigate to project folder and activate your virtual environment.

Install Luxtelligence lnoi400 pdk by changing the file permissions of lnoi_gdsfactory_setup.sh to make it executable,

```bash
chmod +x lnoi400_gdsfactory_setup.sh
```
Then we can execute the file

```bash
./lnoi400_gdsfactory_setup.sh
```


