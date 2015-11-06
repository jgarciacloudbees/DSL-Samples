<H1>Application release sample</H1>

<H2>Platform Requirements</H2>
<p>ElectricFlow 6.1

<H2>Instructions</H2>
<ul>
<li>Retrieve these file to a location on the EF server
<li>Edit the "dslDir" in assemble.groovy to point to where this file is located on the EF server
<li>Run the following from the command line on the EF server
```
ectool login <user> <password>
ectool evalDsl --dslFile "assemble.groovy"
ectool runProcedure "On line bank Release" --procedureName "Assemble"
```

<li>Navigate to Releases in ElectricFlow.  You should see the new Release "Quarterly Online Banking Release"
<ul>