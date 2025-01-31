<script>
import {InputChip} from "@skeletonlabs/skeleton";
</script>

<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<div class="container h-full mx-auto ">

<div class="  shadow-2xl bg-surface-500 m-20">
	<header class="flex justify-center"> GPA calucleter</header>
	<div id="overall gpa">
		GPA all:
	</div>
	<div id="gpa of the semster">
		GPA of the semster:
	</div>
	<div class="p-3 px-2.5 ">
		<div> least gpa:<InputChip id="old gpa"></InputChip></div>
	<div> course name: <InputChip id="corse name"></InputChip></div>
	<div>course hours:<InputChip id="course hours"></InputChip></div>
	<div> the grade :<InputChip id="grade of course"></InputChip></div>
	<button class="border-4 border-pink-500 ">add course</button>
</div>

	</div>
</div>