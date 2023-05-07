Download Link: https://assignmentchef.com/product/solved-operatingsystems-assignment-data-structures-and-functions
<br>
<h2><strong>Data Structures and Functions</strong></h2>




<ul>

 <li>Design and implement the <strong>extended</strong> version of the manager, including:

  <ul>

   <li>PCB, RCB, and RL data structures</li>

   <li>functions <em>create(), destroy(), request()</em>, <em>release()</em>, <em>timeout(), scheduler(), init()</em></li>

  </ul></li>

 <li>Design and implement the shell (see command language and output specifications)</li>

 <li>Instantiate manager to include the following at start-up:

  <ul>

   <li>A process descriptor array PCB[16]</li>

   <li>A resource descriptor array RCB[4] with multiunit resources

    <ul>

     <li>RCB[0] and RCB[1] have 1 unit each; RCB[2] has 2 units; RCB[3] has 3 units</li>

    </ul></li>

   <li>A 3-level RL</li>

  </ul></li>

 <li>The init function should always perform the following tasks:

  <ul>

   <li>Erase all previous contents of the data structures PCB, RCB, RL</li>

   <li>Create a single running process at PCB[0] with priority 0</li>

   <li>Enter the process into the RL at the lowest-priority level 0</li>

  </ul></li>

</ul>


