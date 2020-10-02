--in executor, put

local general = loadstring(path)()

--and then you can use by doing

--(example function)
for i,v in pairs(general.get_players()) do
print(v)
end
