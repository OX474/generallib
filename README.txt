FOR GENERAL LIB

--in executor, put

local general = loadstring(game:HttpGet('https://raw.githubusercontent.com/ProjectCryptid/generallib/main/main',true))()

--and then you can use by doing

--(example function)
for i,v in pairs(general.get_players()) do
print(v)
end

FOR CONSOLE

--in executor, put

local console = loadstring(game:HttpGet('https://raw.githubusercontent.com/ProjectCryptid/generallib/main/burnosSimpleConsole',true))()

--and then you can use by doing

--(example function)
console:init()
console.print("lol")
