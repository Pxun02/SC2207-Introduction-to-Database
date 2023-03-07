# Staffs

Staffs(Staff_ID, Position, Date_Hired)
<!-- * (A, B, C, D) -->

Keys:
<pre>
	Staff_ID
	<!-- * A -->
</pre>

Primary Key:
<pre>
	Staff_ID
	<!-- * A -->
</pre>

FDs:
<pre>
	Staff_ID -> Position,
	<!-- * A -> B -->

	Staff_ID -> Date_Hired
	<!-- * A -> C -->
</pre>

The relation is 3NF.

# Technical Staffs

Technical Staffs(Staff_ID, Laboratory_Name)
<!-- * (A, B) -->

Keys: 
<pre>
	Staff_ID, 
	<!-- * A -->
	Laboratory_Name
	<!-- *B -->
</pre>
Primary Key: 
<pre>
	Staff_ID
	<!-- * A -->
</pre>

FDs: -

The relation is 3NF.

# Administrative Staffs

Administrative Staffs(Staff_ID)
<!-- * A -->

Keys: 
<pre>
	Staff_ID
	<!-- * A -->
</pre>

Primary Key: 
<pre>
	Staff_ID
	<!-- * A -->
</pre>

FDs: -

The relation is 3NF.