<script>
import {InputChip} from "@skeletonlabs/skeleton";
</script>

<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<div class="container  mx-auto ">

<div class="  shadow-2xl bg-surface-500 m-20  ">
	<header class="flex justify-center font-bold"> GPA calucleter</header>
	<div class="border-4  h-[200px] ">
	<div id="overall gpa" class=" m-10">
		GPA all:
	</div>
	<div id="gpa of the semster" class=" m-10">
		GPA of the semster:
	</div>
	</div>
	<div class="p-3 px-2.5 ">
		<div> last gpa:<div class="font-mono">if you don't have it, write 0</div><InputChip id="old gpa" ></InputChip></div>
	<div class="fiex  ">
		<div> course name: <InputChip id="corse name"></InputChip></div>
	<div>course hours:<InputChip id="course hours"></InputChip></div>
	<div> the grade :<InputChip id="grade of course"></InputChip></div>
	</div>
	<button class="border-4 border-pink-500 ">add course</button>
</div>

	</div>
</div>