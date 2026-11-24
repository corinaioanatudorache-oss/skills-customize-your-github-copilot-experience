# 📘 Assignment: Automated Python Checks with GitHub Actions

## 🎯 Objective

Create a GitHub Actions workflow that runs an existing Python test suite automatically whenever code is pushed or a pull request is opened.

## 📝 Tasks

### 🛠️ Set Up the Workflow

#### Description
Add the starter workflow to your repository in the `.github/workflows/` directory, rename it `python-tests.yml`, and confirm that it runs on pushes and pull requests.

#### Requirements
Completed workflow should:

- Use the `push` and `pull_request` events as triggers
- Run on `ubuntu-latest`
- Be visible in the repository's Actions tab
- Be committed and pushed to GitHub

### 🛠️ Configure the Python Environment

#### Description
Complete the workflow steps that check out the repository, set up Python, and install any dependencies.

#### Requirements
Completed workflow should:

- Use `actions/checkout`
- Use `actions/setup-python`
- Select Python 3.12
- Install dependencies from `requirements.txt`
- Run `python -m unittest discover -v`

### 🛠️ Test Success and Failure

#### Description
Push a passing version of the code and inspect the successful workflow run. Then make a small change that breaks a test, push it in a new commit or pull request, and confirm that GitHub Actions reports the failure.

#### Requirements
Completed work should:

- Show at least one successful workflow run
- Show at least one failing workflow run
- Include a final commit that fixes the failing code and restores a successful run
- Be able to explain which step failed and how the test output helped identify the problem

