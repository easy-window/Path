# Path Libraries

This is a Windows path related operation library. Including path decomposition, splicing, obtaining, creating, browsing and so on.

## Usage

```cpp
#include "Path.h"
using namespace Easy;

CString sPath = _T("C:\\Users\\Administrator\\Download\\example.jpg");

Path::GetFileName(sPath);   // example.jpg
Path::GetDirectory(sPath);  // C:\Users\Administrator\Download\ 
Path::GetExtName(sPath);    // .jpg
```
