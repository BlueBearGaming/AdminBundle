v0.2:
Features:
x add column sort
x handle basic permissions
x add dynamic admin or config by event
x add exporters
x basic documentation
x changing admin generated routes default names with dots

Bug fixes :
x fixing bug in list with array fields (doctrine "array" type")
x fixing bug when User is null if 404 permissions method
x fixing bug if a prefix was added in routing admin routing import
x fixing empty text on deletion when an entity have no label property
x fixing bug in filename when exporting (always .csv)
x fixing bug in date time fields when exporting
x fixing bug in array fields when exporting
x fixing bug in action configuration merge on export property (is override)

v0.3:
Features:
- file exporters : array type, association
- adding mass edit
- add filters
- add possibility to have tab in generated forms
- unit testing
- handle custom actions for edit form (enable user for example)
- add configuration for custom url for actions (waiting for ActionBundle)
- improve admin and action name from request (use default parameters in routing instead
- handling new Symfony bootstrap layout
- configure application date format (filename export, displayed date...)

Bug fixes :
- fix bug when deleting entity with integrity constraint
- fix bug with FOSUser column sorting
- fixing columns order in export

v0.4:
