Format
------

`{QUESTION NUMBER}|{START TIME}|{END TIME}|{USER TOKEN}|{QUESTION INDEX}|{ASSESSMENT}|{JUSTIFICATION}|{RECONSIDERATION}`

<dl>
  <dt>QUESTION NUMBER</dt>
  <dd>Integer representing the question id / number.</dd>

  <dt>START TIME</dt>
  <dd>UNIX time stamp of the start time for this question for a worker.</dd>

  <dt>END TIME</dt>
  <dd>UNIX time stamp of the end time for this question for a worker.</dd>

  <dt>USER TOKEN</dt>
  <dd>MD5 hash unique for each worker in the experiment.</dd>

  <dt>QUESTION INDEX</dt>
  <dd>Index this question was shown in the experiment for this worker.</dd>

  <dt>ASSESSMENT</dt>
  <dd>The worker's initial response to the question.</dd>

  <dt>JUSTIFICATION</dt>
  <dd>The free-from text the worker submitted as their justification - empty string if no justification task was assigned to this worker.</dd>

  <dt>RECONSIDERATION</dt>
  <dd>Empty string if no reconsideration task was assigned to this worker, true if the worker switched their answer, and false otherwise.</dd>
</dl>
