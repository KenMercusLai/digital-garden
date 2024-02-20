---
{"dg-publish":true,"permalink":"/daily/how-to-setup-a-local-dev-environment-in-airflow/"}
---

The concept is showing as following
  ![image.png](/img/user/assets/image_1638763289548_0.png)
- Setup process:
	- 1. A running Airflow server within docker
	- The following steps are applied on the local dev computer
		- 2. install docker and docker-compose
		- 3. `git clone https://github.com/ninja-van/airflow-boilerplate.git && cd airflow-boilerplate`
		- 4. install virtualenv and create a new venv
		  ```shell
		  pip install virtualenv
		  virtualenv .venv
		  ```
		- 5. Activate the venv and install packages as required. This step may take a long time.
		  ```shell
		  source .venv/bin/activate
		  pip install -r requirements-airflow.txt
		  pip install -r requirements-dev.txt
		  ```
			- if you face any conflict of packages, you can comment the lines of pandas in `requirements-airflow.txt`
			- You may need to remove specified version of snappy in `requirements-airflow.txt` and leave it to pip to resolve which version to install
		- 6. Initializing airflow `docker-compose -f docker/docker-compose.yml up -d airflow_initdb`
		-