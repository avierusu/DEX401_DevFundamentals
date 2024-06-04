# DEX401: Developer Fundamentals with MuleSoft
This GitHub repo was created to document the exercises that I plan to do with the self-paced DEX401 course.

### This repo includes:
 - RAML specifications
 - Mule projects for all walkthrough exercises
	 - Process APIs
	 - System APIs
 - DIY exercises
 - My personal notes

### When your Anypoint Platform account is updated, make the following changes:

 - Get your new organization ID (groupId) from your Anypoint Platform account:
	 - Go to *Anypoint Platform > Access Management > Business Groups > Your business group > Business Group ID*, copy your **Business Group ID**
 - Open your project's *pom.xml*. Within the *properties* section, update the following elements with new *groupId* and *version*:
```
<american.flights.spec.group.id>your_group_id</american.flights.spec.group.id>
<american.flights.spec.artifact.id>american-flights-api</american.flights.spec.artifact.id>
<american.flights.spec.version>1.0.0</american.flights.spec.version>
```