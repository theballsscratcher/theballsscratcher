```
local function import(filename)
  return loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/theballsscratcher/theballsscratcher/nec/"..filename))()
end
import("necui")
import("necmain")
import("necsettings")
 ```
