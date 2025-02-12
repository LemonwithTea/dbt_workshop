# DBT_WORKSHOP
## Follow this steps:
```sh 
git clone <repo>
cd <repo>
```
(last step if you don't already have virtualenv installed)
```sh
pip install virtualenv
```
Initialize enviroment:
```sh
python -m venv venv
source venv/scripts/activate
pip install -r requirements.txt
```
Set some enviroment variables:
```sh
export DBT_HOST=<bullshit>
export DBT_USER=<bullshit>
export DBT_PASSWORD=<bullshit>
export DBT_DATABASE=<bullshit>
```
### That's all, you can run dbt models.