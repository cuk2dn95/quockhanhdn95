Have to change some attributes in database:
1. position table :
	Must change its name into "rule".
	*Reason:
	The "position" name has taken for a reserved name in MYSQL ( "position()" function).
2. position table and team table :
	Must change both "id" attributes  into integer and auto increment.
	*Reason:
	In UI,We just permit user to input position and team name.The ID can not be generated.