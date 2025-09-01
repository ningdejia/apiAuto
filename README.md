# apiAuto
Automated interface testing based on online shopping malls

Framework Structure
- base: Encapsulation of the base class and test case tools
- common: Encapsulation of common methods
- conf: Directory for storing global configuration files
- data: Path for storing test data
- logs: Directory for storing test logs
- report: Directory for generating test reports, currently supports two types of report generation
- testcase: Directory for storing test case files- venv: Virtual environment used by this framework
- conftest.py: Global operations; the name is fixed and cannot be changed
- environment.xml: Overview of allure test report - environment display content
- extract.yaml: File for storing interface dependency parameters
- pytest.ini: Specification constraints of the pytest framework; the name is fixed and cannot be changed
- requirements.txt: Third-party libraries used by this framework- run.py: Main program entry
