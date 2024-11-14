# Already Ran Script
```
if _G.ScriptRanFlagExample then
print("Script already ran, exiting...")
return
end
_G.ScriptRanFlagExample = true

print("Script is running for the first time...")

-- rest of your script code goes here

print("Script execution complete.")
```
