# editorial_sim
Arena-based simulation of editorial workflows

This repo contains 2 workflow simulation files designed to run in the Arena software package from Rockwell Software:

* Existing_process.doe -- models an existing editorial process by a part-time editor working 18 hours a week.

* New_process.doe -- models a new editorial process to be managed by a full-time editor. Note that, to account for the editorial lead time needed to produce stories, it is necessary to simulate 2 weeks of work instead of one to provide realistic output; so to derive the actual hours worked and number of stories published, halve the numbers shown in the output report.
