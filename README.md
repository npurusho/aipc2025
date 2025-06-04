## AMD NPU Examples and Assignment
### Clone the Repo

##### Copy the below code and run it in a Jupyter notebook in the Ryzen™ AI AUP Cloud 
---
```Python
!pip install pygit2

import pygit2

# URL of the Git repository
repo_url = "https://github.com/npurusho/uic.git"

# Path to clone into
local_path = "./uic"

# Clone the repo
repo = pygit2.clone_repository(repo_url, local_path)

print("Repo cloned at:", repo.workdir)
```
---
