# Alkatraz-Prison-Island
This json mod adds an Alkatraz Prison Island to your Chernarus Server. Influenced by Alcatraz, but does not look like it.

Notes: Performance veries for every device [Xbox, PlayStation, or PC] there may be lag little or alot or not at all. It is recommended that you need to boost prison and police loot to compensate for this mod. Infected Spawns are finicky when trying to spawn them on platforms, so you may or may not see any.

For the best results stop your server before making any changes. Especially when uploading the Areaflags.map file.

Unzip and Upload the areaflags.map file in the dayzOffline.Chernarus main folder, it will automatically replace the vanilla version.

In your Custom folder add the AlkatrazByXMC.json file

In your cfggameplay.json file under WorldsData; comment the json file to spawn the mod. [Below is an example]

	"WorldsData":
	{
		"lightingConfig": 1,
		"objectSpawnersArr": 
		[
		"./custom/test1.json",
		"./custom/test2.json",
		"./custom/AlkatrazByXMC.json"
		],
		"environmentMinTemps": [-5, -5, -5, -5, -5, -5, -5, -5, -5, -5, -5, -5],
		"environmentMaxTemps": [5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5],
		"wetnessWeightModifiers": [1.0, 1.15, 1.35, 1.65, 2.0]
	},

Add a new line in your zombies_territory.xml and add;

    <territory color="2583625983">
        <zone name="InfectedPrisoner" smin="0" smax="0" dmin="10" dmax="20" x="14347" y="18" z="9632" r="40"/>
        <zone name="InfectedPrisoner" smin="0" smax="0" dmin="10" dmax="20" x="14370" y="15" z="9581" r="40"/>
    </territory>

Add a new line your mapgrouppos.xml and add;

  <group name="Land_Prison_Main_Alk" pos="14337.705078 35.075726 9616.304688" rpy="-0.000000 0.000000 -72.457466" a="162.457"/>
	<group name="Land_Prison_Main_Alk" pos="14348.404297 35.066784 9650.560547" rpy="-0.000000 0.000000 77.054070" a="12.9459"/>
	<group name="Land_Prison_Wall_Large_Alk" pos="14377.623047 17.477173 9622.238281" rpy="-0.000000 0.000000 55.916950" a="34.083"/>
	<group name="Land_Prison_Wall_Large_Alk" pos="14346.087891 17.477173 9581.147461" rpy="-0.000000 0.000000 -120.662254" a="-149.338"/>
	<group name="Land_Prison_Wall_Large_Alk" pos="14392.788086 17.477173 9593.875000" rpy="-0.000000 0.000000 38.767300" a="51.2327"/>
	<group name="Land_Prison_Side_Alk" pos="14410.697266 20.726257 9563.491211" rpy="-0.000000 0.000000 38.630764" a="51.3692"/>
	<group name="Land_Prison_Main_Alk" pos="14367.036133 32.199200 9569.760742" rpy="-0.000000 0.000000 -155.688110" a="-114.312"/>
	<group name="Land_Lighthouse" pos="14317.566406 23.542377 9644.537109" rpy="-0.000000 0.000000 -104.241829" a="-165.758"/>
	<group name="Land_Lighthouse" pos="14385.915039 23.891735 9640.503906" rpy="-0.000000 0.000000 129.757980" a="-39.758"/>
	<group name="Land_Lighthouse" pos="14428.368164 22.483448 9548.265625" rpy="-0.000000 0.000000 138.758163" a="-48.7582"/>
	<group name="Land_Lighthouse" pos="14322.958984 24.409512 9593.302734" rpy="-0.000000 0.000000 -158.241837" a="-111.758"/>
	<group name="Land_Mil_GuardTower" pos="14326.877930 16.046961 9671.304688" rpy="-0.000000 0.000000 71.932594" a="18.0674"/>
	<group name="Land_Mil_ControlTower" pos="14379.095703 26.075043 9604.412109" rpy="-0.000000 0.000000 60.495701" a="29.5043"/>
	<group name="Land_Misc_Well_Pump_Blue" pos="14347.876953 15.169184 9583.018555" rpy="-0.000000 0.000000 0.000000" a="90"/>
	<group name="Land_Medical_Tent_Big" pos="14357.891602 14.733630 9570.053711" rpy="-0.000000 0.000000 115.281418" a="-25.2814"/>
	<group name="Land_Medical_Tent_Shower" pos="14358.037109 16.305395 9583.613281" rpy="-0.000000 -0.000000 53.999985" a="36"/>
	<group name="Land_Medical_Tent_Big" pos="14348.873047 14.733630 9595.866211" rpy="-0.000000 0.000000 -117.000000" a="-153"/>
	<group name="Land_Medical_Tent_Big" pos="14355.651367 14.733630 9599.344727" rpy="-0.000000 0.000000 -117.000038" a="-153"/>
	<group name="Land_Mil_Tent_Big1_1" pos="14367.814453 17.617258 9631.537109" rpy="-0.000000 0.000000 77.010361" a="12.9896"/>
	<group name="Land_Mil_Tent_Big2_1" pos="14352.454102 19.614782 9642.031250" rpy="-0.000000 0.000000 -12.662563" a="102.663"/>
	<group name="Land_Mil_Tent_Big2_5" pos="14365.281250 19.614408 9622.479492" rpy="-0.000000 0.000000 50.450184" a="39.5498"/>
	<group name="Land_Medical_Tent_Shower" pos="14344.464844 19.189022 9622.263672" rpy="0.000000 0.000000 -71.999947" a="162"/>
	<group name="Land_Medical_Tent_Big" pos="14336.416992 17.617258 9627.234375" rpy="-0.000000 0.000000 -164.550568" a="-105.449"/>
	<group name="Land_Ship_Medium2" pos="14098.908203 0.905388 10015.834961" rpy="-0.000000 -0.000000 89.999901" a="9.91821e-05"/>
	<group name="Land_Farm_WaterTower_Small" pos="14344.573242 23.223503 9582.448242" rpy="-0.000000 0.000000 78.365829" a="11.6342"/>
	<group name="Land_Mil_GuardBox_Smooth" pos="14331.985352 14.113318 9675.036133" rpy="-0.000000 0.000000 161.236649" a="-71.2366"/>
	<group name="Land_Guardhouse" pos="14332.458984 4.184754 9684.451172" rpy="-0.000000 0.000000 69.928833" a="20.0712"/>


Add a new line in your mapgroupprotto.xml and add:

		<group name="Land_Prison_Main_Alk" lootmax="50">
        <usage name="Prison" />
				<usage name="Police" />
				<value name="Tier3" />
				<value name="Tier4" />
				<container name="lootFloor">
						<category name="tools" />
						<category name="containers" />
						<category name="clothes" />
						<tag name="floor" />
						<point pos="7.679199 5.079140 6.900146" range="0.673975" height="1.710938" />
						<point pos="3.787599 5.083633 7.847412" range="1.167693" height="2.000000" />
						<point pos="6.014648 -10.205940 -0.173585" range="1.199951" height="2.000000" />
						<point pos="-0.095459 -10.205940 -0.315430" range="1.199951" height="2.000000" />
						<point pos="-11.206547 -10.128014 10.861814" range="1.109343" height="2.000000" />
						<point pos="-16.289307 -10.127960 5.257324" range="1.166657" height="2.000000" />
						<point pos="-18.365480 -10.128052 0.209714" range="1.199951" height="2.000000" />
						<point pos="-14.665773 -10.211342 -9.666258" range="1.053401" height="2.000000" />
						<point pos="-11.333250 -10.211342 -8.186768" range="1.199951" height="2.000000" />
						<point pos="-10.056151 -10.211342 -4.203127" range="1.199951" height="2.000000" />
						<point pos="-9.239746 -10.211342 1.310302" range="1.199951" height="2.000000" />
						<point pos="3.517336 -10.218567 13.264892" range="1.199951" height="2.000000" />
						<point pos="8.505375 -10.205940 9.587157" range="1.199951" height="2.000000" />
						<point pos="8.535648 -13.747330 12.697264" range="1.199951" height="2.000000" />
						<point pos="18.578617 -10.205940 15.236813" range="1.199951" height="2.000000" />
						<point pos="18.719236 -10.205940 10.175049" range="1.199951" height="2.000000" />
						<point pos="19.695068 -10.205940 1.739256" range="1.199951" height="2.000000" />
						<point pos="20.841795 -10.205940 -1.667972" range="1.199951" height="2.000000" />
						<point pos="20.636475 -10.205940 -7.252931" range="1.184570" height="2.000000" />
						<point pos="21.259764 -10.205940 -11.162110" range="1.199951" height="2.000000" />
						<point pos="18.514162 -13.747330 14.614011" range="1.199951" height="2.000000" />
						<point pos="19.256105 -13.747330 10.086177" range="1.199951" height="2.000000" />
						<point pos="20.698730 -13.747330 3.806394" range="1.199951" height="2.000000" />
						<point pos="20.712648 -13.747330 -2.585938" range="1.199951" height="2.000000" />
						<point pos="18.411865 -13.747330 -6.917971" range="1.199951" height="2.000000" />
						<point pos="18.604980 -13.747330 -11.376709" range="1.199951" height="2.000000" />
						<point pos="0.507567 -13.747330 16.291748" range="1.199951" height="2.000000" />
						<point pos="-10.983888 -13.747330 9.010983" range="1.199951" height="2.000000" />
						<point pos="-13.007082 -13.747330 6.419921" range="1.199951" height="2.000000" />
						<point pos="-15.752439 -13.747330 4.583007" range="1.199951" height="2.000000" />
						<point pos="-18.210938 -13.747330 1.361569" range="1.028225" height="2.000000" />
						<point pos="-13.831294 -13.772118 -11.052739" range="1.199951" height="2.000000" />
						<point pos="-12.387207 -13.772125 -7.702147" range="1.199951" height="2.000000" />
						<point pos="-9.262938 -13.772125 -4.514406" range="1.199951" height="2.000000" />
						<point pos="-11.406738 -17.415161 -2.243897" range="1.199951" height="2.000000" />
						<point pos="-18.714111 -17.415161 1.852782" range="1.199951" height="2.000000" />
						<point pos="-15.940920 -17.415161 4.796385" range="1.199951" height="2.000000" />
						<point pos="-12.948485 -17.415161 7.213865" range="1.048576" height="2.000000" />
						<point pos="-11.126953 -17.415161 10.572020" range="1.159757" height="2.000000" />
						<point pos="-9.321779 -17.415161 12.974117" range="1.013013" height="2.000000" />
						<point pos="4.948489 -17.415161 16.657715" range="1.039063" height="2.000000" />
						<point pos="3.460451 -17.415161 13.255615" range="1.178051" height="2.000000" />
						<point pos="8.822026 -17.415161 11.050047" range="1.199951" height="2.000000" />
						<point pos="18.445559 -17.415161 15.331786" range="1.199951" height="2.000000" />
						<point pos="20.175537 -17.415161 10.037110" range="1.199951" height="2.000000" />
						<point pos="20.559570 -17.415161 3.423338" range="1.199951" height="2.000000" />
						<point pos="19.677734 -17.386490 -1.552004" range="1.199951" height="2.000000" />
						<point pos="21.042234 -17.386490 -6.013428" range="1.199951" height="2.000000" />
						<point pos="20.981197 -17.386490 -11.211670" range="1.199951" height="2.000000" />
				</container>
				<container name="lootshelves">
						<category name="tools" />
						<category name="containers" />
						<category name="clothes" />
						<tag name="shelves" />
						<point pos="3.066162 -9.337517 -3.576416" range="0.546875" height="1.367188" />
						<point pos="7.129639 -9.337517 -3.543946" range="0.503662" height="1.259155" />
						<point pos="9.073975 -9.337517 -3.533693" range="0.487305" height="1.218262" />
						<point pos="-11.956544 -9.794815 9.067381" range="0.625624" height="0.533653" />
						<point pos="-14.680908 -9.794815 7.937006" range="0.575905" height="0.532387" />
						<point pos="-17.156740 -9.003677 3.807863" range="0.579013" height="1.447532" />
						<point pos="-19.914797 -9.794815 2.117187" range="0.615625" height="0.532440" />
						<point pos="-20.741943 -9.003586 1.401853" range="0.509269" height="1.273170" />
						<point pos="-15.902834 -9.794815 -10.592038" range="0.546875" height="0.533661" />
						<point pos="-13.922119 -9.794815 -5.458010" range="0.535509" height="0.532486" />
						<point pos="-13.138428 -9.004936 -3.849854" range="0.546875" height="1.367188" />
						<point pos="-8.490233 -9.794815 -2.204348" range="0.528259" height="0.532425" />
						<point pos="-7.623291 -9.005005 0.778565" range="0.421387" height="1.053467" />
						<point pos="-7.655518 -9.794815 1.820311" range="0.453613" height="0.533585" />
						<point pos="4.246342 -9.312485 15.205811" range="0.443750" height="1.109375" />
						<point pos="1.561278 -9.312485 15.222657" range="0.443750" height="1.109375" />
						<point pos="9.863041 -9.547012 17.010498" range="0.306250" height="0.765625" />
						<point pos="10.022950 -9.377068 11.687498" range="0.100000" height="0.250000" />
						<point pos="6.959231 -9.757065 11.782469" range="0.134375" height="0.264999" />
						<point pos="6.956054 -8.997070 9.438721" range="0.100000" height="0.250000" />
						<point pos="10.028563 -9.377068 9.487305" range="0.100000" height="0.250000" />
						<point pos="9.978759 -10.132065 8.239990" range="0.134375" height="0.259995" />
						<point pos="6.963383 -9.757065 16.509520" range="0.134375" height="0.264999" />
						<point pos="6.942139 -9.377068 15.442628" range="0.134375" height="0.264999" />
						<point pos="19.778566 -9.792374 13.463377" range="0.478125" height="0.533493" />
						<point pos="20.412598 -9.002487 17.004633" range="0.409375" height="1.023438" />
						<point pos="19.781738 -9.792374 11.837403" range="0.478125" height="0.533638" />
						<point pos="21.095703 -9.001740 8.889400" range="0.478125" height="1.195313" />
						<point pos="17.777102 -9.001747 8.312744" range="0.478125" height="1.195313" />
						<point pos="18.715822 -9.792374 5.995848" range="0.478125" height="0.532425" />
						<point pos="21.538816 -9.002632 4.663815" range="0.443750" height="1.109375" />
						<point pos="21.750242 -9.001114 2.339839" range="0.443750" height="1.109375" />
						<point pos="21.894531 -9.792374 1.190186" range="0.478125" height="0.532387" />
						<point pos="18.672361 -9.792374 -3.542238" range="0.409375" height="0.532501" />
						<point pos="20.218752 -9.001114 -3.348147" range="0.409375" height="1.023438" />
						<point pos="18.919920 -9.792374 -5.259037" range="0.512500" height="0.532463" />
						<point pos="20.820311 -9.792374 -5.163332" range="0.443750" height="0.533707" />
						<point pos="18.565430 -9.001137 -12.104005" range="0.375000" height="0.937500" />
						<point pos="20.772947 -9.001900 -9.691649" range="0.409375" height="1.023438" />
						<point pos="12.045899 -9.337524 -9.514405" range="0.512500" height="0.214989" />
						<point pos="9.830571 -13.100723 16.825926" range="0.340625" height="0.851563" />
						<point pos="6.991943 -13.310776 17.288818" range="0.134375" height="0.264999" />
						<point pos="10.021728 -13.310776 9.490967" range="0.100000" height="0.250000" />
						<point pos="10.064211 -12.930779 10.285398" range="0.134375" height="0.264999" />
						<point pos="6.976076 -12.930779 9.227538" range="0.134375" height="0.264999" />
						<point pos="6.968508 -13.310776 11.927000" range="0.134375" height="0.264999" />
						<point pos="7.000490 -13.685776 14.411133" range="0.100000" height="0.250000" />
						<point pos="18.156492 -13.346535 17.099119" range="0.478125" height="0.532616" />
						<point pos="12.058593 -16.671516 -9.566651" range="0.486136" height="0.201149" />
						<point pos="19.654547 -13.346535 11.824215" range="0.478125" height="0.533653" />
						<point pos="19.934572 -13.346535 8.267574" range="0.478125" height="0.533752" />
						<point pos="17.558840 -13.346535 8.411131" range="0.443750" height="0.533546" />
						<point pos="17.366943 -13.346535 5.331296" range="0.443750" height="0.533127" />
						<point pos="21.306396 -13.346535 5.878172" range="0.443750" height="0.532326" />
						<point pos="20.905762 -13.346535 1.020507" range="0.478125" height="0.533318" />
						<point pos="20.264160 -12.555336 -0.899170" range="0.478125" height="1.195313" />
						<point pos="18.426027 -12.556259 -3.532716" range="0.443750" height="1.109375" />
						<point pos="17.940916 -12.555412 -5.196290" range="0.478125" height="1.195313" />
						<point pos="20.488768 -13.346535 -7.834475" range="0.478125" height="0.533607" />
						<point pos="21.396482 -13.346535 -9.554445" range="0.443750" height="0.533043" />
						<point pos="21.401365 -13.346535 -12.259767" range="0.478125" height="0.533051" />
						<point pos="12.013915 -12.977364 -9.483644" range="0.546875" height="0.206863" />
						<point pos="-0.289062 -12.977364 -3.533691" range="0.512500" height="1.281250" />
						<point pos="5.626464 -13.100723 16.083494" range="0.340625" height="0.851563" />
						<point pos="5.893312 -13.310776 13.398925" range="0.100000" height="0.250000" />
						<point pos="5.841798 -13.310776 11.731688" range="0.134375" height="0.264999" />
						<point pos="4.138184 -12.930779 11.274658" range="0.139143" height="0.264999" />
						<point pos="3.309819 -13.685776 12.091307" range="0.134375" height="0.259995" />
						<point pos="1.783447 -13.100723 12.892579" range="0.271875" height="0.679688" />
						<point pos="-11.218505 -13.337608 11.318357" range="0.615625" height="0.532402" />
						<point pos="-14.245120 -13.337608 7.865477" range="0.684375" height="0.532845" />
						<point pos="-16.253174 -13.337608 3.108394" range="0.410352" height="0.532280" />
						<point pos="-17.223631 -13.337608 3.822752" range="0.505998" height="0.533730" />
						<point pos="-19.234863 -13.337608 0.142572" range="0.615625" height="0.533348" />
						<point pos="-15.367431 -12.550522 -8.537113" range="0.478125" height="1.195313" />
						<point pos="-14.627197 -13.341560 -4.961667" range="0.537926" height="0.533531" />
						<point pos="-13.015624 -12.550323 -3.776611" range="0.443750" height="1.109375" />
						<point pos="-9.820801 -13.341560 -0.996338" range="0.578322" height="0.533653" />
						<point pos="-13.811037 -16.730309 -12.048583" range="0.375000" height="0.937500" />
						<point pos="-14.889890 -16.956718 -8.677735" range="0.134375" height="0.335938" />
						<point pos="-11.887451 -16.943268 -5.392335" range="0.100000" height="0.250000" />
						<point pos="-8.767820 -16.943268 -6.141603" range="0.189897" height="0.264999" />
						<point pos="-8.873534 -16.730309 -1.693359" range="0.425024" height="1.062559" />
						<point pos="-10.354492 -16.730309 -0.248292" range="0.408106" height="1.020264" />
						<point pos="-13.522460 -16.563271 -1.780031" range="0.185791" height="0.264999" />
						<point pos="-19.667967 -16.975380 0.344971" range="0.603527" height="0.532501" />
						<point pos="-17.239260 -16.184250 3.908201" range="0.596276" height="1.490690" />
						<point pos="-14.538820 -16.975380 6.606199" range="0.606979" height="0.533653" />
						<point pos="-11.867920 -16.975380 9.098875" range="0.546875" height="0.532288" />
						<point pos="-7.849124 -16.184509 13.566405" range="0.443750" height="1.109344" />
						<point pos="-0.268318 -16.509399 15.129884" range="0.443750" height="1.109375" />
						<point pos="2.228031 -16.509399 15.249511" range="0.443750" height="1.109375" />
						<point pos="17.233648 -16.981743 16.958000" range="0.443750" height="0.533806" />
						<point pos="20.301519 -16.981743 13.607662" range="0.512500" height="0.532822" />
						<point pos="20.350588 -16.191452 11.768555" range="0.443750" height="1.109375" />
						<point pos="17.886721 -16.191101 8.509272" range="0.443750" height="1.109375" />
						<point pos="17.630859 -16.981743 6.001220" range="0.512500" height="0.533730" />
						<point pos="20.434570 -16.981743 5.781734" range="0.478125" height="0.533379" />
						<point pos="18.058838 -16.981743 -3.427003" range="0.443750" height="0.533234" />
						<point pos="20.394287 -16.981743 -7.862062" range="0.478125" height="0.533722" />
						<point pos="18.953854 -16.981743 -5.177736" range="0.500244" height="0.532425" />
						<point pos="18.905762 -16.981743 -12.290039" range="0.443750" height="0.532761" />
						<point pos="20.194334 -16.981743 -9.565675" range="0.443750" height="0.533691" />
						<point pos="9.551269 -16.674553 -3.553223" range="0.548629" height="1.292427" />
						<point pos="3.256347 -16.674561 -3.528564" range="0.512500" height="1.281250" />
						<point pos="20.552492 -13.346535 17.140623" range="0.443750" height="0.532288" />
				</container>
				<container name="lootweapons" lootmax="3">
						<category name="weapons" />
						<point pos="7.054443 5.079140 2.965087" range="0.756480" height="1.891197" />
						<point pos="1.710205 5.079185 0.256103" range="0.743896" height="1.859741" />
						<point pos="-3.041748 5.079140 4.402832" range="0.718750" height="1.796875" />
						<point pos="-3.017577 5.079140 6.908447" range="0.684375" height="1.710938" />
						<point pos="0.488281 -0.349564 0.511719" range="0.718750" height="1.796875" />
						<point pos="4.197265 -0.349556 0.513672" range="0.718750" height="1.796875" />
						<point pos="-5.285157 -10.205940 15.729492" range="1.199951" height="2.000000" />
						<point pos="-13.184572 -10.128052 6.930173" range="1.199951" height="2.000000" />
						<point pos="5.405765 -9.312485 13.136230" range="0.340625" height="0.851563" />
						<point pos="10.060306 -9.377068 13.119871" range="0.100000" height="0.250000" />
						<point pos="6.944825 -9.377068 13.921876" range="0.100000" height="0.250000" />
						<point pos="6.939212 -9.377068 8.185057" range="0.100000" height="0.250000" />
						<point pos="10.014161 -9.377068 8.622069" range="0.134375" height="0.264999" />
						<point pos="9.976807 -9.757065 10.388914" range="0.100000" height="0.250000" />
						<point pos="10.031741 -10.132065 12.082273" range="0.134375" height="0.259995" />
						<point pos="6.949217 -9.377068 17.004639" range="0.100000" height="0.250000" />
						<point pos="16.791504 -10.205940 -14.462890" range="0.614746" height="1.536865" />
						<point pos="12.026367 -9.337524 -12.878418" range="0.475778" height="1.189445" />
						<point pos="6.942383 -13.685776 16.103514" range="0.100000" height="0.250000" />
						<point pos="6.974365 -12.930779 14.418210" range="0.134375" height="0.264999" />
						<point pos="10.076419 -12.930779 11.187251" range="0.100000" height="0.250000" />
						<point pos="10.051758 -12.550781 9.083007" range="0.100000" height="0.250000" />
						<point pos="8.508546 -13.747330 8.903810" range="1.199951" height="2.000000" />
						<point pos="8.559572 -10.218567 14.138426" range="1.199951" height="2.000000" />
						<point pos="6.986330 -13.310776 10.908690" range="0.100000" height="0.250000" />
						<point pos="6.953859 -12.930779 8.206542" range="0.134375" height="0.264999" />
						<point pos="12.064940 -12.977364 -6.100099" range="0.478125" height="1.195313" />
						<point pos="3.011230 -12.977364 -3.568359" range="0.546875" height="1.311134" />
						<point pos="3.553713 -13.310776 11.855957" range="0.134375" height="0.264999" />
						<point pos="5.024660 -13.310776 11.092284" range="0.156250" height="0.264999" />
						<point pos="5.875732 -12.930779 12.541991" range="0.100000" height="0.250000" />
						<point pos="4.240234 -13.747330 13.699952" range="1.199951" height="2.000000" />
						<point pos="-0.419922 -13.100723 12.827392" range="0.340625" height="0.851563" />
						<point pos="-12.210694 -16.563271 -5.070313" range="0.150536" height="0.264999" />
						<point pos="-8.982178 -17.403236 -4.186524" range="1.199951" height="2.000000" />
						<point pos="-13.839354 -16.943268 -2.087892" range="0.134375" height="0.264999" />
						<point pos="5.480956 -16.509399 11.634767" range="0.443750" height="1.109375" />
						<point pos="21.674805 -13.775536 -14.175293" range="0.865967" height="2.000000" />
				</container>
		</group>
		<group name="Land_Prison_Side_Alk" lootmax="15">
				<usage name="Prison" />
        <usage name="Police" />
				<value name="Tier3" />
				<value name="Tier4" />
				<container name="lootFloor" lootmax="8">
						<category name="tools" />
						<category name="containers" />
						<category name="clothes" />
						<tag name="floor" />
						<point pos="3.875488 -5.868248 2.643310" range="0.597900" height="1.494749" />
						<point pos="4.916993 -5.871872 -1.145508" range="0.749527" height="1.873817" />
						<point pos="-5.232912 -5.858055 7.650877" range="0.823975" height="2.000000" />
						<point pos="3.458496 -5.871307 -1.739258" range="0.825195" height="2.000000" />
						<point pos="-8.742678 -5.850815 13.906980" range="0.864258" height="2.000000" />
						<point pos="3.448975 -5.874725 -6.210205" range="0.875773" height="0.197493" />
						<point pos="-4.224854 -5.856201 10.996580" range="1.031738" height="2.000000" />
						<point pos="-8.566165 -5.853523 10.532712" range="1.040771" height="0.517332" />
						<point pos="3.295898 -5.874451 -5.995117" range="1.199951" height="0.209318" />
						<point pos="-3.844726 -5.865494 -0.805421" range="1.060488" height="2.000000" />
						<point pos="-0.790773 -6.091110 4.257080" range="1.115723" height="2.000000" flags="32" />
						<point pos="-0.043700 -6.209251 7.818115" range="1.125244" height="2.000000" flags="32" />
						<point pos="-0.090332 -6.072556 -11.193115" range="1.171875" height="2.000000" flags="32" />
						<point pos="-0.116944 -6.072556 1.232666" range="1.198486" height="2.000000" flags="32" />
						<point pos="-0.364013 -6.072556 -7.258789" range="1.199951" height="2.000000" flags="32" />
						<point pos="4.573486 -5.867462 4.308349" range="1.199951" height="2.000000" />
						<point pos="8.218262 -5.865189 10.602781" range="1.199951" height="0.164446" />
						<point pos="5.049805 -5.868027 4.005371" range="1.199951" height="2.000000" />
						<point pos="5.147460 -5.878136 -9.119873" range="1.199951" height="2.000000" />
						<point pos="4.995605 -5.871239 -0.243653" range="1.199951" height="2.000000" />
						<point pos="-0.394043 -6.072556 -3.013427" range="1.199951" height="2.000000" flags="32" />
						<point pos="4.291505 -5.862923 9.992432" range="1.199951" height="2.000000" />
						<point pos="-5.763671 -5.867592 -5.305176" range="1.199951" height="2.000000" />
						<point pos="-0.456791 -6.349945 13.485352" range="1.199951" height="2.000000" flags="32" />
				</container>
				<container name="lootshelves" lootmax="8">
						<category name="tools" />
						<category name="containers" />
						<category name="clothes" />
						<tag name="shelves" />
						<point pos="7.404786 -5.866600 8.016845" range="0.100000" height="0.250000" />
						<point pos="7.422365 -5.866539 8.113280" range="0.100000" height="0.250000" />
						<point pos="7.410647 -5.867111 7.359617" range="0.100000" height="0.250000" />
						<point pos="7.440920 -4.263229 7.022459" range="0.100000" height="0.250000" />
						<point pos="8.145995 -4.671143 -11.257323" range="0.100000" height="0.250000" />
						<point pos="7.724854 -4.670883 -11.297852" range="0.100000" height="0.250000" />
						<point pos="5.978271 -5.880363 -11.279784" range="0.100000" height="0.250000" />
						<point pos="4.905518 -5.879631 -11.306641" range="0.100000" height="0.250000" />
						<point pos="3.887697 -5.878906 -11.281493" range="0.100000" height="0.250000" />
						<point pos="4.226561 -5.879143 -11.283203" range="0.100000" height="0.250000" />
						<point pos="2.777343 -5.878136 -11.288818" range="0.100000" height="0.250000" />
						<point pos="3.170411 -5.878418 -11.302734" range="0.100000" height="0.250000" />
						<point pos="-4.772703 -5.858948 6.909425" range="0.100000" height="0.250000" />
						<point pos="-6.781493 -5.865471 -3.455080" range="0.100000" height="0.250000" />
						<point pos="-5.872558 -4.261940 -3.448488" range="0.100000" height="0.250000" />
						<point pos="-6.745605 -5.865509 -3.476564" range="0.100000" height="0.250000" />
						<point pos="6.447998 -5.782524 7.042724" range="0.100000" height="0.250000" />
						<point pos="4.789063 -5.781403 6.991943" range="0.100000" height="0.250000" />
						<point pos="4.595948 -5.407181 5.795654" range="0.100000" height="0.250000" />
						<point pos="4.582520 -5.409866 2.271240" range="0.100000" height="0.250000" />
						<point pos="5.951660 -5.414284 -2.252442" range="0.100000" height="0.250000" />
						<point pos="5.997070 -5.788383 -1.035645" range="0.100000" height="0.250000" />
						<point pos="6.035644 -5.412590 0.039306" range="0.100000" height="0.250000" />
						<point pos="4.926270 -5.785934 1.194824" range="0.100000" height="0.250000" />
						<point pos="5.998780 -5.791260 -4.794434" range="0.100000" height="0.250000" />
						<point pos="6.053466 -5.416817 -5.473633" range="0.100000" height="0.250000" />
						<point pos="6.008301 -5.792892 -6.916992" range="0.100000" height="0.250000" />
						<point pos="4.870605 -5.792122 -6.951416" range="0.100000" height="0.250000" />
						<point pos="-5.840332 -4.262001 -3.500000" range="0.134375" height="0.335938" />
						<point pos="6.984130 -5.881042 -11.250977" range="0.134375" height="0.335938" />
						<point pos="7.442871 -5.866302 8.444824" range="0.134375" height="0.335938" />
						<point pos="4.635741 -5.789291 -3.465820" range="0.134375" height="0.259998" />
						<point pos="5.988526 -5.790672 -4.037110" range="0.134375" height="0.260000" />
						<point pos="4.831787 -5.413582 -2.355714" range="0.134375" height="0.264999" />
						<point pos="4.354006 -5.864151 8.438719" range="0.134375" height="0.335938" />
						<point pos="5.918946 -4.263496 5.279783" range="0.134375" height="0.335938" />
						<point pos="5.731201 -5.407021 7.041504" range="0.134375" height="0.264999" />
						<point pos="-4.919190 -5.869507 -7.036133" range="0.134375" height="0.335938" />
						<point pos="6.005616 -5.783607 5.216552" range="0.134375" height="0.260000" />
						<point pos="6.038087 -5.409370 4.256590" range="0.134375" height="0.265001" />
						<point pos="5.998779 -5.409966 3.432374" range="0.134375" height="0.264999" />
						<point pos="6.023194 -5.785736 2.454345" range="0.134375" height="0.260000" />
						<point pos="-6.140626 -5.872795 -12.457275" range="0.160156" height="0.400390" />
						<point pos="5.928466 -4.266762 1.022460" range="0.168750" height="0.421875" />
						<point pos="5.509767 -5.869301 2.759520" range="0.217819" height="0.544547" />
						<point pos="4.248045 -5.015549 -12.411132" range="0.237500" height="0.593750" />
						<point pos="4.294436 -4.784340 11.627194" range="0.237500" height="0.369999" />
						<point pos="4.517334 -5.868622 2.742675" range="0.257544" height="0.643860" />
						<point pos="-4.691894 -5.865913 -2.128418" range="0.271875" height="0.679688" />
						<point pos="4.660403 -5.784538 11.697265" range="0.271875" height="0.369999" />
						<point pos="7.537109 -5.863922 11.639647" range="0.306250" height="0.639446" />
						<point pos="-3.709717 -5.860741 5.531494" range="0.321896" height="0.804740" />
						<point pos="8.117433 -5.864555 11.344970" range="0.340625" height="0.639446" />
						<point pos="2.513428 -5.866386 3.828857" range="0.340625" height="0.851563" />
						<point pos="5.840331 -5.876785 -6.728759" range="0.340625" height="0.823910" />
						<point pos="2.272463 -5.862915 8.156737" range="0.443750" height="1.109375" />
						<point pos="3.444582 -5.863701 8.193357" range="0.443750" height="1.109375" />
						<point pos="-6.495365 -5.856270 8.836423" range="0.478125" height="0.639448" />
						<point pos="-4.920896 -5.871017 -9.012451" range="0.478125" height="1.195313" />
				</container>
				<container name="lootweapons" lootmax="8">
						<category name="weapons" />
            <category name="explosives" />
						<point pos="5.957763 -5.880287 -11.201902" range="0.100000" height="0.250000" />
						<point pos="4.220214 -5.879089 -11.216796" range="0.100000" height="0.250000" />
						<point pos="4.697754 -5.026299 7.041260" range="0.100000" height="0.250000" />
						<point pos="5.983888 -5.410522 2.691894" range="0.100000" height="0.250000" />
						<point pos="5.982422 -5.784119 4.531738" range="0.100000" height="0.250000" />
						<point pos="5.067628 -5.782516 5.787353" range="0.100000" height="0.250000" />
						<point pos="6.016357 -5.787163 0.578368" range="0.100000" height="0.250000" />
						<point pos="4.801758 -5.030876 1.150634" range="0.100000" height="0.250000" />
						<point pos="5.972656 -5.413582 -1.315186" range="0.100000" height="0.250000" />
						<point pos="6.017334 -5.789070 -1.912354" range="0.100000" height="0.250000" />
						<point pos="5.018067 -5.037292 -7.038086" range="0.100000" height="0.250000" />
						<point pos="6.041015 -5.417580 -6.477051" range="0.100000" height="0.250000" />
						<point pos="6.050780 -5.415398 -3.620362" range="0.100000" height="0.250000" />
						<point pos="5.032714 -5.414589 -3.488770" range="0.100000" height="0.250000" />
						<point pos="5.947021 -5.417076 -5.908936" range="0.134375" height="0.264999" />
						<point pos="4.912841 -5.879608 -11.266113" range="0.134375" height="0.335938" />
						<point pos="4.992919 -5.030159 2.265869" range="0.134375" height="0.264999" />
						<point pos="6.023193 -5.416252 -4.765137" range="0.134375" height="0.265001" />
						<point pos="3.151855 -5.878395 -11.285156" range="0.134375" height="0.335938" />
						<point pos="6.022217 -5.408340 5.584228" range="0.134375" height="0.264999" />
						<point pos="5.985595 -5.411812 1.012694" range="0.134375" height="0.264999" />
						<point pos="-5.476073 -4.262245 -3.493897" range="0.134375" height="0.335938" />
						<point pos="6.012695 -5.412895 -0.384766" range="0.134375" height="0.264999" />
						<point pos="2.540040 -5.866371 3.880126" range="0.306250" height="0.765625" />
						<point pos="-5.284423 -5.865448 -2.061769" range="0.322935" height="0.807337" />
						<point pos="4.283204 -5.868370 2.854247" range="0.340625" height="0.851563" />
						<point pos="6.902833 -5.863647 11.425781" range="0.340625" height="0.639444" />
						<point pos="-6.465820 -5.857292 7.525878" range="0.443750" height="0.639448" />
						<point pos="2.104980 -5.872520 -4.558105" range="0.237500" height="0.593750" />
						<point pos="4.526128 -5.284431 11.719236" range="0.237500" height="0.369999" />
						<point pos="-5.248291 -5.873421 -12.461182" range="0.159180" height="0.397950" />
						<point pos="7.450440 -5.867065 7.447020" range="0.163574" height="0.408935" />
						<point pos="8.722412 -5.864655 11.762449" range="0.203125" height="0.507813" />
						<point pos="-4.506350 -5.860245 5.455321" range="0.478125" height="1.195313" />
						<point pos="8.127930 -5.866852 8.353514" range="1.199951" height="2.000000" />
						<point pos="5.775879 -5.865662 7.757812" range="0.931152" height="2.000000" />
						<point pos="-7.690188 -5.854118 10.553708" range="1.191162" height="2.000000" />
				</container>
		</group>
		<group name="Land_Prison_Wall_Large_Alk" lootmax="5">
				<usage name="Prison" />
        <usage name="Police" />
				<value name="Tier3" />
				<value name="Tier4" />
				<container name="lootFloor">
						<category name="tools" />
						<category name="containers" />
						<category name="clothes" />
						<category name="weapons" />
						<category name="explosives" />
						<tag name="floor" />
						<tag name="shelves" />
						<point pos="1.269047 0.954124 10.218261" range="0.815186" height="2.000000" />
						<point pos="0.597167 0.938553 -15.373780" range="0.946045" height="2.000000" />
						<point pos="1.484375 0.951569 6.307861" range="0.960937" height="2.000000" />
						<point pos="0.622559 0.947540 -0.933105" range="0.996094" height="2.000000" />
						<point pos="-3.729980 0.944672 -9.523927" range="1.033203" height="2.000000" />
						<point pos="4.372316 0.955009 14.481444" range="1.199951" height="0.100002" />
						<point pos="-3.053954 0.942413 -12.528320" range="1.174316" height="2.000000" />
						<point pos="-2.111328 0.947205 -3.984131" range="1.199951" height="2.000000" />
						<point pos="-1.328857 0.950829 2.545898" range="1.199951" height="2.000000" />
						<point pos="2.712646 0.944626 -3.694336" range="1.199951" height="2.000000" />
						<point pos="-1.691406 0.939323 -16.232422" range="1.199951" height="2.000000" />
						<point pos="-4.182860 0.948479 -14.849121" range="1.199951" height="2.000000" />
				</container>
		</group>
