# README

The docs are deployed at: https://trisolaris-labs.github.io/docs/

* Docs are made using [mkdocs](https://www.mkdocs.org/)


### Setup
1. Clone the repo
2. Create a virtual enviornment 

```
    virtualenv -p python3.8 venv
    source venv/bin/activate
``` 
3. Install dependencies `pip install -r requirements.txt`
4. Start a local server `mkdocs serve`
5. Make changes and update local/origin master
6. Once you make an update, github actions will automatically build and deploy the latest master version.