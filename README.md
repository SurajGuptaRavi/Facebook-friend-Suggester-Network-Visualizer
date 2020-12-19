# Facebook-friend-Suggester-Network-Visualizer
  Installations
<ul>
<li>pip install dash</li>
<li>pip install dash_cytoscape</li>
</ul>
<br>
 <b>Working Flow:<b>
 <br>
<br>
<b> Object Creation & Connection</b>
<ol>
<li>Create more than one user objects.</li>
<li>Create the facebook object.</li>
<li>Connect the users with (facebook object).connect_user method.
</li>
<li>provide user1 & user2 as a parameters for connecting user1 and user2.
</li>
</ol>

<b>providing suggestion for user1</b>
<ol>
<li>use (facebook object).suggest_for method and pass the user1 object as a parametr for suggesting friends for user1.</li>
</ol>

<b>Network Visualization</b>
<ol>
<li>call the (facebook object).draw_network method it will return the list of connections. </li>
<li>store that connections in network variable. </li>
<li>pass the stored connection in the dashapp. </li>
</ol>
