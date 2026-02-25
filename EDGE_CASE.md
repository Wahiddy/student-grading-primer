# Document your edge case here
- To get marks for this section you will need to explain to your tutor:
1) The edge case you identified

If there are no students in the DB, then what stats should the /stats route return.

2) How you have accounted for this in your implementation

If no students are in the DB then just return {"count": 0, "average": 0, "min": 0, "max": 0} with 200 status code