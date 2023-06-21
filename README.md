# Attack-Bar
A little modification to the addon Attack Bar from Udokus to return the remaining swing time

<br />
Added this line of code<br />

```
function ABarSwingTimers()
	return Abar_Mhr.st, Abar_Oh.st, rs
end
```
If the function is called in another addon or macro it returns the remaining swing time of your MH and OH.
