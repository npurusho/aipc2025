## AMD NPU Examples and Assignment

Clone this repo using:
```Python
!pip install pygit2

import pygit2

# URL of the Git repository
repo_url = "https://github.com/npurusho/sjsu.git"

# Path to clone into
local_path = "./sjsu"

# Clone the repo
repo = pygit2.clone_repository(repo_url, local_path)

print("Repo cloned at:", repo.workdir)

```
