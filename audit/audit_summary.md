# Audit summary

Summary for [Jenkins instance](http://localhost:8080)

- GitHub Actions Importer version: **1.3.19590 (eb26dd19ab2bc8507c1cadd4a86e858bdfd15dd0)**
- Performed at: **6/21/23 at 09:15**

## Pipelines

Total: **3**

- Successful: **2 (66%)**
- Partially successful: **1 (33%)**
- Unsupported: **0 (0%)**
- Failed: **0 (0%)**

### Job types

Supported: **3 (100%)**

- project: **2**
- flow-definition: **1**

### Build steps

Total: **17**

Known: **7 (41%)**

- container: **3**
- hudson.tasks.Shell: **3**
- hudson.plugins.git.GitPublisher: **1**

Unsupported: **10 (58%)**

- script: **9**
- hudson.tasks.Mailer: **1**

Actions: **14**

- actions/checkout@v3.5.0: **10**
- run: **4**

### Triggers

Total: **1**

Known: **1 (100%)**

- hudson.triggers.TimerTrigger: **1**

Actions: **3**

- workflow_dispatch: **2**
- schedule: **1**

### Environment

Total: **5**

Known: **4 (80%)**

- org.jenkinsci.plugins.credentialsbinding.impl.SecretBuildWrapper: **2**
- CREDENTIALS_ID: **1**
- CRED_ID: **1**

Unknown: **1 (20%)**

- GIT_CREDENTIALS: **1**

Actions: **4**

- CRED_ID: **1**
- CREDENTIALS_ID: **1**
- first-var: **1**
- EXPRESSION_VAR: **1**

### Other

Total: **4**

Unknown: **4 (100%)**

- disableConcurrentBuilds: **1**
- buildDiscarder: **1**
- skipDefaultCheckout: **1**
- timestamps: **1**

### Manual tasks

Total: **3**

Secrets: **2**

- `${{ secrets.SECRET_TEST_EXPRESSION_VAR }}`: **1**
- `${{ secrets.EXPRESSION_FIRST_VAR }}`: **1**

Self hosted runners: **1**

- `DemoRunner`: **1**

### Successful

#### monas_dev_work/monas_freestyle

- [monas_dev_work/monas_freestyle/.github/workflows/monas_freestyle.yml](monas_dev_work/monas_freestyle/.github/workflows/monas_freestyle.yml)
- [monas_dev_work/monas_freestyle/config.json](monas_dev_work/monas_freestyle/config.json)

#### test_freestyle_project

- [test_freestyle_project/.github/workflows/test_freestyle_project.yml](test_freestyle_project/.github/workflows/test_freestyle_project.yml)
- [test_freestyle_project/config.json](test_freestyle_project/config.json)

### Partially successful

#### TestPipeline

- [TestPipeline/.github/workflows/testpipeline.yml](TestPipeline/.github/workflows/testpipeline.yml)
- [TestPipeline/config.json](TestPipeline/config.json)
- [TestPipeline/jenkinsfile](TestPipeline/jenkinsfile)
