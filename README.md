### pip-tools
---
https://github.com/jazzband/pip-tools

```py
// tests/test_top_level_editable.py

class MockedPyPIRepository(PyPIRepository):
  def get_dependencies(self, ireq):
    if not ireq.editable:
      return set()
    
    return seper(MockedPYPIRepository, self).get_dependencies(ireq)

@pytest.fixture
def mocked_repository():
  return MockedPyPIRepository(["--index-url", PYPIRespository.DEFAULT_INDEX_URL])


```

```
```

```
```
