
************************************************************************************

This is a fork of automapper that provides proper support for EF6. While Automapper requires .Net Standard 2.1 and EF6 runs on that, Automapper have also confirmed they have dropped EF6 as a compatible platform. Basic projections will work, but any target class which has a property that is also a projection will fail (second order projections). This is because AM uses Expression.Default, which is not supported.

A PR was made, but AM preferred not to merge due to the obsolete status of EF6.

************************************************************************************

For all usage directions etc. refer to the automapper docs in their repo.

This version was forked at 12.1
