# psputpowershelltowork

## 3. Extending the Shell
### 4 Putting PowerShell to Work
```
Get-PSSnapin -Registered
```

## 7. PowerShell Formatting
### 1 The Formatting Process
```
$pshome
get-service bits
get-service | get-member name
select-string system.servceprocess.servicecontroller -context 0.30|more
```



### 8 Demonstration: Format-list
```
help format-list
get-alias -definition format-list
```
custom
```
get-vegetable | format-list
get-vegetable | fl *
get-vegetable | fl name,count
get-vegetable | fl name,count,@{Name="Status";Expression={$_.cookedstate}}
```
