<style type="text/css">
	table.tableizer-table {
	border: 1px solid #CCC;
	font-size: 12.5px;
} 
.tableizer-table td {
	border: 2px solid #ccc;
}
.tableizer-table th {
	background-color: #008000; 
	color: #FFF;
	font-weight: bold;
}
</style>

#Backend Configurations

- For those interested, this is a listing of some of the tables Evergreen uses to make decisions about hold, circulation and permission policies.
	- If you receive a "Permission Denied" type messsage when attempting to perfom an action in Evergreen, let us know if any of the permissions listed are on this table and we can get you up and running.

##Abbreviated Circulation Rules Table
<hr size=2>

<table class="tableizer-table">
<tr class="tableizer-firstrow"><th>Shortname</th><th>Permission Group</th><th>Circ Modifier</th><th>Renewals?</th><th>Duration Rule</th><th>Recurring Fine Rule</th><th>Max Fine Rule</th><th>id</th></tr>
 <tr><td>BCL-BKM</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>42_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2373</td></tr>
 <tr><td>BCLDIST</td><td>FULL PRIVILEGES</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2406</td></tr>
 <tr><td>BCLDIST</td><td>LIMITED - 12 CKO</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2416</td></tr>
 <tr><td>BCLDIST</td><td>LIMITED - 2 CKO</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2414</td></tr>
 <tr><td>BCLDIST</td><td>LIMITED - 6 CKO</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2415</td></tr>
 <tr><td>BCLDIST</td><td>LIMITED - NO PC</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2417</td></tr>
 <tr><td>BCLDIST</td><td>READY2LEARN</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>05_cent_per_day</td><td>&nbsp;</td><td>2405</td></tr>
 <tr><td>BCLDIST</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2205</td></tr>
 <tr><td>BCLDIST</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2204</td></tr>
 <tr><td>BMCC</td><td>STAFF & FACULTY</td><td>Audiobook Cassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1325</td></tr>
 <tr><td>BMCC</td><td>STAFF & FACULTY</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_3D_7D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2214</td></tr>
 <tr><td>BMCC</td><td>STAFF & FACULTY</td><td>Hourly Reserves</td><td>&nbsp;</td><td>2H_2H_2H_0</td><td>20_cent_per_hour</td><td>&nbsp;</td><td>2213</td></tr>
 <tr><td>BMCC</td><td>STAFF & FACULTY</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>2208</td></tr>
 <tr><td>BMCC</td><td>STUDENT - ACADEMIC</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_3D_7D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2215</td></tr>
 <tr><td>BMCC</td><td>STUDENT - ACADEMIC</td><td>Hourly Reserves</td><td>&nbsp;</td><td>2H_2H_2H_0</td><td>20_cent_per_hour</td><td>&nbsp;</td><td>2212</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>Cassette</td><td>&nbsp;</td><td>14_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2210</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>CD</td><td>&nbsp;</td><td>14_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2209</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>3D_3D_3D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2217</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>3D_3D_3D_2</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1315</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>Music CD</td><td>&nbsp;</td><td>14_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2211</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>Pamphlet</td><td>&nbsp;</td><td>3D_3D_3D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2216</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1322</td></tr>
 <tr><td>BMCC</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2207</td></tr>
 <tr><td>CGCC</td><td>STAFF & FACULTY</td><td>Daily Reserves</td><td>&nbsp;</td><td>3D_3D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2220</td></tr>
 <tr><td>CGCC</td><td>STAFF & FACULTY</td><td>Hourly Reserves</td><td>&nbsp;</td><td>3H_3H_24H_1</td><td>20_cent_per_hour</td><td>&nbsp;</td><td>2224</td></tr>
 <tr><td>CGCC</td><td>STUDENT - ACADEMIC</td><td>Daily Reserves</td><td>&nbsp;</td><td>3D_3D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2219</td></tr>
 <tr><td>CGCC</td><td>STUDENT - ACADEMIC</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_7D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2221</td></tr>
 <tr><td>CGCC</td><td>STUDENT - ACADEMIC</td><td>Hourly Reserves</td><td>&nbsp;</td><td>3H_3H_24H_1</td><td>20_cent_per_hour</td><td>&nbsp;</td><td>2223</td></tr>
 <tr><td>CGCC</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_7D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2413</td></tr>
 <tr><td>CGCC</td><td>Users</td><td>ILL Material</td><td>&nbsp;</td><td>28_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2375</td></tr>
 <tr><td>CGCC</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2218</td></tr>
 <tr><td>CGCC-HR</td><td>STUDENT - ACADEMIC</td><td>Daily Reserves</td><td>&nbsp;</td><td>3D_3D_7D_1</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1105</td></tr>
 <tr><td>CGCC-HR</td><td>STUDENT - ACADEMIC</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_7D_0</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1106</td></tr>
 <tr><td>CGCC-HR</td><td>STUDENT - ACADEMIC</td><td>Hourly Reserves</td><td>&nbsp;</td><td>3H_3H_24H_1</td><td>20_cent_per_hour</td><td>0_00</td><td>1027</td></tr>
 <tr><td>FOS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>5_00</td><td>2340</td></tr>
 <tr><td>GC-ARL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2256</td></tr>
 <tr><td>GC-ARL</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2257</td></tr>
 <tr><td>GC-ARL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2255</td></tr>
 <tr><td>GC-CONHS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2261</td></tr>
 <tr><td>GC-GCL</td><td>Users</td><td>Computer/Laptop</td><td>&nbsp;</td><td>1D_1D_1D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2260</td></tr>
 <tr><td>GC-GCL</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>3D_3D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2259</td></tr>
 <tr><td>GC-GCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2258</td></tr>
 <tr><td>GR-GCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2262</td></tr>
 <tr><td>HC-CRANE</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2266</td></tr>
 <tr><td>HC-HCL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2264</td></tr>
 <tr><td>HC-HCL</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2265</td></tr>
 <tr><td>HC-HCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day_5dygrace</td><td>5_00</td><td>2263</td></tr>
 <tr><td>HR-CLL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day_3dygrace</td><td>1_00</td><td>2348</td></tr>
 <tr><td>HR-HRCL</td><td>Users</td><td>ILL Material</td><td>&nbsp;</td><td>21_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2378</td></tr>
 <tr><td>HR-HRCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day_3dygrace</td><td>1_00</td><td>2347</td></tr>
 <tr><td>HR-HRHS</td><td>PATRON</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2433</td></tr>
 <tr><td>HR-HRHS</td><td>STAFF & FACULTY</td><td>Memory Stick</td><td>&nbsp;</td><td>1_day_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2272</td></tr>
 <tr><td>HR-HRHS</td><td>STAFF & FACULTY</td><td>&nbsp;</td><td>&nbsp;</td><td>42_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2273</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HIGH SCHOOL</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2269</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HIGH SCHOOL</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2420</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HIGH SCHOOL</td><td>Memory Stick</td><td>&nbsp;</td><td>1_day_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2270</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HIGH SCHOOL</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2432</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HS SENIOR</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2268</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HS SENIOR</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2421</td></tr>
 <tr><td>HR-HRHS</td><td>STUDENT - HS SENIOR</td><td>Memory Stick</td><td>&nbsp;</td><td>1_day_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2271</td></tr>
 <tr><td>HR-HRHS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2267</td></tr>
 <tr><td>HR-PCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day_3dygrace</td><td>1_00</td><td>2349</td></tr>
 <tr><td>HRDIST</td><td>FULL PRIVILEGES</td><td>Book Club Kits</td><td>&nbsp;</td><td>42_days_0_renew</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2434</td></tr>
 <tr><td>HRDIST</td><td>FULL PRIVILEGES</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day_3dygrace</td><td>1_00</td><td>2402</td></tr>
 <tr><td>HRDIST</td><td>INSTITUTION</td><td>Book</td><td>&nbsp;</td><td>28_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2429</td></tr>
 <tr><td>HRDIST</td><td>INSTITUTION</td><td>DVD</td><td>&nbsp;</td><td>28_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2428</td></tr>
 <tr><td>HRDIST</td><td>INSTITUTION</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2427</td></tr>
 <tr><td>HRDIST</td><td>INSTITUTION</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2426</td></tr>
 <tr><td>HRDIST</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>7d7d21d_HRCLD_DVD</td><td>&nbsp;</td><td>&nbsp;</td><td>2407</td></tr>
 <tr><td>HRDIST</td><td>Users</td><td>Ephemera</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2391</td></tr>
 <tr><td>HRDIST</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>21_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2389</td></tr>
 <tr><td>HRDIST</td><td>Users</td><td>Museum Passes</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2390</td></tr>
 <tr><td>HSL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2206</td></tr>
 <tr><td>KC-KFCC</td><td>STUDENT - ACADEMIC</td><td>Hourly Reserves</td><td>&nbsp;</td><td>1H_2H_3H_3</td><td>&nbsp;</td><td>&nbsp;</td><td>2435</td></tr>
 <tr><td>LCLDIST</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2275</td></tr>
 <tr><td>LCLDIST</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2276</td></tr>
 <tr><td>LCLDIST</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>15_cent_per_day</td><td>5_00</td><td>2274</td></tr>
 <tr><td>MC-NYSSA</td><td>Users</td><td>Computer/Laptop</td><td>&nbsp;</td><td>1D_1D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2278</td></tr>
 <tr><td>MC-NYSSA</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2395</td></tr>
 <tr><td>MC-NYSSA</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2277</td></tr>
 <tr><td>MC-NYSSA</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2396</td></tr>
 <tr><td>MC-OHS</td><td>STUDENT - HIGH SCHOOL</td><td>Book</td><td>&nbsp;</td><td>1D_1D_1D_2</td><td>50_cent_per_day</td><td>25_00</td><td>2343</td></tr>
 <tr><td>MC-OHS</td><td>STUDENT - HIGH SCHOOL</td><td>Book</td><td>&nbsp;</td><td>21D_21D_21D_2</td><td>05_cent_per_day</td><td>25_00</td><td>1205</td></tr>
 <tr><td>MC-OHS</td><td>STUDENT - HIGH SCHOOL</td><td>DVD</td><td>&nbsp;</td><td>5D_5D_5D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2280</td></tr>
 <tr><td>MC-OHS</td><td>STUDENT - HIGH SCHOOL</td><td>Periodical</td><td>&nbsp;</td><td>5D_5D_5D_0</td><td>50_cent_per_day</td><td>7_00</td><td>2281</td></tr>
 <tr><td>MC-OHS</td><td>STUDENT - HIGH SCHOOL</td><td>Textbook</td><td>&nbsp;</td><td>1D_1D_1D_2</td><td>50_cent_per_day</td><td>25_00</td><td>2357</td></tr>
 <tr><td>MC-OHS</td><td>STUDENT - HIGH SCHOOL</td><td>Videocassette</td><td>&nbsp;</td><td>5D_5D_5D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2282</td></tr>
 <tr><td>MC-OHS</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>5D_5D_5D_0</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1112</td></tr>
 <tr><td>MC-OHS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2279</td></tr>
 <tr><td>MC-OMS</td><td>STUDENT - MIDDLE SCHOOL</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2376</td></tr>
 <tr><td>MC-OMS</td><td>STUDENT - MIDDLE SCHOOL</td><td>Periodical</td><td>&nbsp;</td><td>5D_5D_5D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2283</td></tr>
 <tr><td>MC-OMS</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>5D_5D_5D_0</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1059</td></tr>
 <tr><td>MC-OMS</td><td>Users</td><td>Reading Program Book</td><td>&nbsp;</td><td>21D_21D_21D_1</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1057</td></tr>
 <tr><td>MC-OMS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2284</td></tr>
 <tr><td>MC-VHS</td><td>STUDENT - HIGH SCHOOL</td><td>Audiobook Cassette</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2287</td></tr>
 <tr><td>MC-VHS</td><td>STUDENT - HIGH SCHOOL</td><td>Audiobook CD</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2289</td></tr>
 <tr><td>MC-VHS</td><td>STUDENT - HIGH SCHOOL</td><td>Periodical</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2286</td></tr>
 <tr><td>MC-VHS</td><td>Users</td><td>Audiobook Cassette</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1085</td></tr>
 <tr><td>MC-VHS</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>7D_7D_7D_1</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1060</td></tr>
 <tr><td>MC-VHS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2285</td></tr>
 <tr><td>OTLD</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2292</td></tr>
 <tr><td>OTLD</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2291</td></tr>
 <tr><td>OTLD</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2293</td></tr>
 <tr><td>OTLD</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>21_days_2_renew</td><td>20_cent_per_day</td><td>5_00</td><td>2381</td></tr>
 <tr><td>PIERCE</td><td>ILL</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_0_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2353</td></tr>
 <tr><td>PIERCE</td><td>STAFF & FACULTY</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2341</td></tr>
 <tr><td>PIERCE</td><td>STAFF & FACULTY</td><td>CD</td><td>&nbsp;</td><td>1D_3D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2235</td></tr>
 <tr><td>PIERCE</td><td>STAFF & FACULTY</td><td>DVD</td><td>&nbsp;</td><td>3D_3D_3D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2342</td></tr>
 <tr><td>PIERCE</td><td>STAFF & FACULTY</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2247</td></tr>
 <tr><td>PIERCE</td><td>STAFF & FACULTY</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>0_50_1_00_1_25_1_day</td><td>10_00</td><td>2191</td></tr>
 <tr><td>PIERCE</td><td>STAFF & FACULTY</td><td>Summit ILL</td><td>&nbsp;</td><td>6D_42</td><td>&nbsp;</td><td>&nbsp;</td><td>2246</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - ACADEMIC</td><td>Computer/Laptop</td><td>&nbsp;</td><td>4H_4H_4H_2</td><td>10_00_10_00_10_00_1_hour</td><td>120_00</td><td>2231</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - ACADEMIC</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_3D_7D_3</td><td>&nbsp;</td><td>&nbsp;</td><td>2230</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - ACADEMIC</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2249</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - ACADEMIC</td><td>Hourly Reserves</td><td>&nbsp;</td><td>1H_2H_3H_3</td><td>0_01_0_25_0_50_1_hour</td><td>10_00</td><td>2226</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - ACADEMIC</td><td>Summit ILL</td><td>&nbsp;</td><td>6D_42</td><td>50_cent_per_day</td><td>20_00</td><td>2244</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - DISTANCE</td><td>Computer/Laptop</td><td>&nbsp;</td><td>4H_4H_4H_2</td><td>10_00_10_00_10_00_1_hour</td><td>120_00</td><td>2232</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - DISTANCE</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_3D_7D_3</td><td>&nbsp;</td><td>&nbsp;</td><td>2229</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - DISTANCE</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2248</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - DISTANCE</td><td>Hourly Reserves</td><td>&nbsp;</td><td>1H_2H_3H_3</td><td>0_01_0_25_0_50_1_hour</td><td>&nbsp;</td><td>2228</td></tr>
 <tr><td>PIERCE</td><td>STUDENT - DISTANCE</td><td>Summit ILL</td><td>&nbsp;</td><td>6D_42</td><td>50_cent_per_day</td><td>20_00</td><td>2245</td></tr>
 <tr><td>PIERCE</td><td>SUMMIT INSTITUTION</td><td>Book</td><td>&nbsp;</td><td>53_days</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2352</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Cassette</td><td>&nbsp;</td><td>3D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2253</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>CD</td><td>&nbsp;</td><td>3D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2252</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_3D_7D_3</td><td>50_cent_per_day</td><td>10_00</td><td>1010</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>1D_3D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2233</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>0_50_1_00_1_25_1_day</td><td>10_00</td><td>2192</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Film</td><td>&nbsp;</td><td>1D_3D_7D_3</td><td>0_50_1_00_1_00_1_day</td><td>10_00</td><td>1011</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>ILL Material</td><td>&nbsp;</td><td>28_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2250</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Music Cassette</td><td>&nbsp;</td><td>3D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2254</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Music CD</td><td>&nbsp;</td><td>3D_7D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2251</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>1D_3D_7D_1</td><td>&nbsp;</td><td>&nbsp;</td><td>2234</td></tr>
 <tr><td>PIERCE</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>25_cent_per_day</td><td>10_00</td><td>2225</td></tr>
 <tr><td>SAGE</td><td>EDUCATOR</td><td>&nbsp;</td><td>&nbsp;</td><td>42_days_2_renew</td><td>0_00_0_00_0_00_1_day</td><td>&nbsp;</td><td>2430</td></tr>
 <tr><td>SAGE</td><td>FULL PRIVILEGES</td><td>Audiobook CD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>25_cent_per_day</td><td>5_00</td><td>1415</td></tr>
 <tr><td>SAGE</td><td>ILL</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2202</td></tr>
 <tr><td>SAGE</td><td>OUTREACH SERVICE</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2203</td></tr>
 <tr><td>SAGE</td><td>STAFF & FACULTY</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2201</td></tr>
 <tr><td>SAGE</td><td>STUDENT - HIGH SCHOOL</td><td>&nbsp;</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2422</td></tr>
 <tr><td>SAGE</td><td>STUDENT - HS SENIOR</td><td>&nbsp;</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2423</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Audiobook Cassette</td><td>&nbsp;</td><td>14D_21D_21D_2</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1114</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Bluray</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2408</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>7_days_2_renew</td><td>20_cent_per_day</td><td>5_00</td><td>2199</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>1D_3D_7D_3</td><td>0_01_0_10_0_20_1_day</td><td>5_25</td><td>1013</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>ereader</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2388</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Hourly Reserves</td><td>&nbsp;</td><td>1H_2H_3H_3</td><td>0_01_0_25_0_50_1_hour</td><td>10_00</td><td>1004</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>ILL Material</td><td>&nbsp;</td><td>28_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2400</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Museum Passes</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2355</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Textbook</td><td>&nbsp;</td><td>7_days_1_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2077</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>7_days_2_renew</td><td>20_cent_per_day</td><td>5_00</td><td>2200</td></tr>
 <tr><td>SAGE</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>14D_21D_28D_2</td><td>20_cent_per_day</td><td>5_00</td><td>2198</td></tr>
 <tr><td>SC-SCPS</td><td>STUDENT - HIGH SCHOOL</td><td>Periodical</td><td>&nbsp;</td><td>7_days_1_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2178</td></tr>
 <tr><td>SC-SCPS</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>7_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2295</td></tr>
 <tr><td>SC-SCPS</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>7_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2296</td></tr>
 <tr><td>SC-SCPS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2294</td></tr>
 <tr><td>TVCC</td><td>STAFF & FACULTY</td><td>&nbsp;</td><td>&nbsp;</td><td>90D_90D_90D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2301</td></tr>
 <tr><td>TVCC</td><td>STAFF & FACULTY</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2298</td></tr>
 <tr><td>TVCC</td><td>STUDENT - ACADEMIC</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_1D_1D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2299</td></tr>
 <tr><td>TVCC</td><td>STUDENT - DISTANCE</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_1D_1D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2300</td></tr>
 <tr><td>TVCC</td><td>Users</td><td>Daily Reserves</td><td>&nbsp;</td><td>1D_1D_1D_2</td><td>0_50_1_00_1_25_1_day</td><td>5_00</td><td>1034</td></tr>
 <tr><td>TVCC</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>3D_3D_3D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2302</td></tr>
 <tr><td>TVCC</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>25_cent_per_day</td><td>5_00</td><td>2297</td></tr>
 <tr><td>UM-ECP</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>2410</td></tr>
 <tr><td>UM-HPL</td><td>INSTITUTION</td><td>DVD</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2310</td></tr>
 <tr><td>UM-HPL</td><td>INSTITUTION</td><td>Periodical</td><td>&nbsp;</td><td>14_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2311</td></tr>
 <tr><td>UM-HPL</td><td>INSTITUTION</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_2_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2303</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>Book Club Kits</td><td>&nbsp;</td><td>42_days_0_renew</td><td>0_50_1_00_1_00_1_day</td><td>20_00</td><td>2314</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>Deposit Required</td><td>&nbsp;</td><td>7_days_2_renew</td><td>0_50_1_00_1_00_1_day</td><td>10_00</td><td>2386</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>Electronics</td><td>&nbsp;</td><td>3D_7D_7D_0</td><td>10_dollar_per_day</td><td>overdue_equip_max</td><td>2387</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>3D_7D_7D_2</td><td>1_dollar_per_day</td><td>10_00</td><td>2315</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>Museum Passes</td><td>&nbsp;</td><td>1D_3D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2316</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>New/High Demand</td><td>&nbsp;</td><td>7D_14D_21D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2354</td></tr>
 <tr><td>UM-HPL</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2317</td></tr>
 <tr><td>UM-MF</td><td>Users</td><td>Computer/Laptop</td><td>&nbsp;</td><td>1_hour_2_renew</td><td>20_cent_per_hour</td><td>&nbsp;</td><td>2318</td></tr>
 <tr><td>UM-MF</td><td>Users</td><td>New/High Demand</td><td>&nbsp;</td><td>7_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2319</td></tr>
 <tr><td>UM-PEN</td><td>FULL PRIVILEGES</td><td>Music Cassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>20_cent_per_day</td><td>5_00</td><td>1420</td></tr>
 <tr><td>UM-PEN</td><td>Users</td><td>Book</td><td>&nbsp;</td><td>7D_21D_28D_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2358</td></tr>
 <tr><td>UM-PEN</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>7_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2320</td></tr>
 <tr><td>UM-PEN</td><td>Users</td><td>Kit</td><td>&nbsp;</td><td>7D_21D_28D_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2403</td></tr>
 <tr><td>UM-PEN</td><td>Users</td><td>Museum Passes</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2359</td></tr>
 <tr><td>UM-SPL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2404</td></tr>
 <tr><td>UM-SPL</td><td>Users</td><td>Museum Passes</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2385</td></tr>
 <tr><td>UM-UPL</td><td>INSTITUTION</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2374</td></tr>
 <tr><td>UM-UPL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>20_cent_per_day_3dygrace</td><td>5_00</td><td>2380</td></tr>
 <tr><td>UN-CS</td><td>STUDENT - ELEMENTARY SCHOOL</td><td>&nbsp;</td><td>&nbsp;</td><td>7D_7D_7D_3</td><td>&nbsp;</td><td>&nbsp;</td><td>2324</td></tr>
 <tr><td>UN-CS</td><td>STUDENT - HIGH SCHOOL</td><td>&nbsp;</td><td>&nbsp;</td><td>14D_14D_14D_3</td><td>&nbsp;</td><td>&nbsp;</td><td>2325</td></tr>
 <tr><td>UN-CS</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2323</td></tr>
 <tr><td>UN-ELP</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>5_00</td><td>2399</td></tr>
 <tr><td>UN-LPL</td><td>EDUCATOR</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_2_renew</td><td>10_cent_per_day</td><td>&nbsp;</td><td>2356</td></tr>
 <tr><td>UN-LPL</td><td>Users</td><td>DVD Box Set</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2418</td></tr>
 <tr><td>UN-LPL</td><td>Users</td><td>New/High Demand</td><td>&nbsp;</td><td>7_days_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2322</td></tr>
 <tr><td>UN-LPL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>10_cent_per_day</td><td>5_00</td><td>2321</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>7_days_2_renew</td><td>05_cent_per_day</td><td>&nbsp;</td><td>2329</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>Equipment</td><td>&nbsp;</td><td>1D_1D_3D_0</td><td>&nbsp;</td><td>&nbsp;</td><td>2379</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>Hourly Reserves</td><td>&nbsp;</td><td>1H_2H_3H_3</td><td>20_cent_per_hour</td><td>&nbsp;</td><td>2393</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>ILL Material</td><td>&nbsp;</td><td>28_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2360</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>Museum Passes</td><td>&nbsp;</td><td>7_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2382</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>New/High Demand</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2327</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2328</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>Playaway</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2377</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>7_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2330</td></tr>
 <tr><td>WC-DALLES</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>21_days_2_renew</td><td>05_cent_per_day</td><td>1_00</td><td>2326</td></tr>
 <tr><td>WC-DUFUR</td><td>STAFF & FACULTY</td><td>Book</td><td>&nbsp;</td><td>28_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2334</td></tr>
 <tr><td>WC-DUFUR</td><td>STUDENT - HIGH SCHOOL</td><td>&nbsp;</td><td>&nbsp;</td><td>14_day_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2332</td></tr>
 <tr><td>WC-DUFUR</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>14_day_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2136</td></tr>
 <tr><td>WC-DUFUR</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>14_day_1_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2333</td></tr>
 <tr><td>WC-DUFUR</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2331</td></tr>
 <tr><td>WC-ENT</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21D_21D_21D_2</td><td>&nbsp;</td><td>&nbsp;</td><td>2365</td></tr>
 <tr><td>WC-ENT</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2366</td></tr>
 <tr><td>WC-ENT</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2361</td></tr>
 <tr><td>WC-JPL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2367</td></tr>
 <tr><td>WC-JPL</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2368</td></tr>
 <tr><td>WC-JPL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2362</td></tr>
 <tr><td>WC-JSY</td><td>Users</td><td>Book</td><td>&nbsp;</td><td>21_days_2_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>1389</td></tr>
 <tr><td>WC-PLANE</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>7D_21D_28D_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2383</td></tr>
 <tr><td>WC-PLANE</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>7D_21D_28D_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2384</td></tr>
 <tr><td>WC-PLANE</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2394</td></tr>
 <tr><td>WC-SWCL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>14_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2336</td></tr>
 <tr><td>WC-SWCL</td><td>Users</td><td>New/High Demand</td><td>&nbsp;</td><td>14_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2337</td></tr>
 <tr><td>WC-SWCL</td><td>Users</td><td>Periodical</td><td>&nbsp;</td><td>14_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2339</td></tr>
 <tr><td>WC-SWCL</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>14_days_0_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2338</td></tr>
 <tr><td>WC-SWCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>28_days_2_renew</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2335</td></tr>
 <tr><td>WC-WAL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2371</td></tr>
 <tr><td>WC-WAL</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2372</td></tr>
 <tr><td>WC-WAL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2364</td></tr>
 <tr><td>WC-WCL</td><td>Users</td><td>DVD</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2369</td></tr>
 <tr><td>WC-WCL</td><td>Users</td><td>Videocassette</td><td>&nbsp;</td><td>21_days_2_renew</td><td>&nbsp;</td><td>&nbsp;</td><td>2370</td></tr>
 <tr><td>WC-WCL</td><td>Users</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>0_00_0_00_0_00_1_day</td><td>0_00</td><td>2363</td></tr>
</table>

##Hold Rules Table
<table class="tableizer-table">
<tr class="tableizer-firstrow"><th>Hold Matchpoint ID</th><th>User Home Library</th><th>Requesting Library</th><th>Pickup Library</th><th>Item Owning Library</th><th>Item Circulating Library</th><th>User Group</th><th>Requestor Group</th><th>Circulation Modifier</th><th>Reference Flag</th><th>Holdable Flag</th><th>Distance is from Owner</th><th>Transit Range Depth</th><th>Max Holds</th><th>Include Frozen Holds Flag</th><th>Stop Blocked User Flag</th><th>Strict Org Unit Match Flag</th></tr>
 <tr><td>522</td><td>CGCC</td><td>&nbsp;</td><td>&nbsp;</td><td>CGCC</td><td>&nbsp;</td><td>&nbsp;</td><td>STUDENT - ACADEMIC</td><td>Textbook</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>t</td></tr>
 <tr><td>524</td><td>CGCC</td><td>&nbsp;</td><td>&nbsp;</td><td>CGCC</td><td>&nbsp;</td><td>&nbsp;</td><td>STAFF & FACULTY</td><td>Textbook</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>t</td></tr>
 <tr><td>593</td><td>LC-CV</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>Circulators</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>584</td><td>LC-CV</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>585</td><td>LC-LK</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>594</td><td>LC-LK</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>Circulators</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>590</td><td>LC-PA</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>595</td><td>LC-PA</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>Circulators</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>596</td><td>LC-SL</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>&nbsp;</td><td>Circulators</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>591</td><td>LC-SL</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>Rental</td><td>f</td><td>t</td><td>f</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>530</td><td>LCLDIST</td><td>LCLDIST</td><td>LCLDIST</td><td>LCLDIST</td><td>&nbsp;</td><td>Users</td><td>Users</td><td>Rental</td><td>f</td><td>t</td><td>t</td><td>1</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>531</td><td>PIERCE</td><td>PIERCE</td><td>&nbsp;</td><td>PIERCE</td><td>PIERCE</td><td>SUMMIT INSTITUTION</td><td>Users</td><td>&nbsp;</td><td>f</td><td>t</td><td>t</td><td>1</td><td>100</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>543</td><td>SAGE</td><td>LCLDIST</td><td>LCLDIST</td><td>LCLDIST</td><td>LCLDIST</td><td>PASSPORT PATRON</td><td>PASSPORT PATRON</td><td>&nbsp;</td><td>f</td><td>t</td><td>t</td><td>2</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>537</td><td>SAGE</td><td>SAGE</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>INSTITUTION</td><td>Users</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>50</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>540</td><td>SAGE</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>30</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>541</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>Staff</td><td>Staff</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>50</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>542</td><td>SAGE</td><td>SAGE</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>PATRON</td><td>Staff</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>100</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>534</td><td>SAGE</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>Users</td><td>PASSPORT PATRON</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>5</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>118</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UM-HPL</td><td>SAGE</td><td>Users</td><td>Users</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>93</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>LC-CV</td><td>LC-CV</td><td>Users</td><td>Users</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>95</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>LC-PA</td><td>LC-PA</td><td>Users</td><td>Users</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>126</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>127</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>Users</td><td>Users</td><td>Kit</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>128</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>Users</td><td>Users</td><td>Periodical</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>129</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>Users</td><td>Users</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>521</td><td>SAGE</td><td>SAGE</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>Users</td><td>Users</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>510</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>ILL</td><td>Staff</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>50</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>538</td><td>SAGE</td><td>SAGE</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>ILL</td><td>Users</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>100</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>357</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>WC-JSY</td><td>WC-JSY</td><td>Users</td><td>Users</td><td>Book</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>562</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>Users</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>563</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>PATRON</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>564</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>FULL PRIVILEGES</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>565</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>Staff</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>566</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>STAFF & FACULTY</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>567</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>Circulators</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>568</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>Local System Administrator</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>569</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>EDUCATOR</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>570</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>LIMITED - 2 CKO</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>572</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>STUDENT - ACADEMIC</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>573</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>PASSPORT PATRON</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>574</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>575</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>PATRON</td><td>PATRON</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>576</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>UN-LPL</td><td>UN-LPL</td><td>FULL PRIVILEGES</td><td>Circulators</td><td>DVD Box Set</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>495</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>LC-LK</td><td>LC-CV</td><td>Users</td><td>Users</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>496</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>LC-LK</td><td>LC-PA</td><td>Users</td><td>Users</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>525</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>EDUCATOR</td><td>Book</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>20</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>529</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>&nbsp;</td><td>Users</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>523</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>CGCC</td><td>&nbsp;</td><td>&nbsp;</td><td>Users</td><td>Textbook</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>520</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>Users</td><td>Users</td><td>Book</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>526</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>EDUCATOR</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>20</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>516</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>PATRON</td><td>PATRON</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>582</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>Circulators</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>581</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>Rental</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>117</td><td>UM-HPL</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>SAGE</td><td>LIMITED - 2 CKO</td><td>LIMITED - 2 CKO</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>559</td><td>UN-LPL</td><td>UN-LPL</td><td>UN-LPL</td><td>UN-LPL</td><td>UN-LPL</td><td>Users</td><td>Users</td><td>DVD Box Set</td><td>f</td><td>t</td><td>t</td><td>2</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>539</td><td>UN-UPL</td><td>&nbsp;</td><td>UN-UPL</td><td>&nbsp;</td><td>&nbsp;</td><td>EDUCATOR</td><td>Staff</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>150</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>597</td><td>UN-UPL</td><td>&nbsp;</td><td>UN-UPL</td><td>&nbsp;</td><td>&nbsp;</td><td>EDUCATOR</td><td>PATRON</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>150</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>599</td><td>UN-UPL</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>EDUCATOR</td><td>PATRON</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>150</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>600</td><td>UN-UPL</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>EDUCATOR</td><td>Staff</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>150</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>514</td><td>WC-PLANE</td><td>WC-PLANE</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>Users</td><td>Users</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>4</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>509</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>Users</td><td>Users</td><td>Book</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>46</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>MC-VHS</td><td>MC-VHS</td><td>Users</td><td>Users</td><td>DVD</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>40</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>MC-VHS</td><td>MC-VHS</td><td>Users</td><td>Users</td><td>Videocassette</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>39</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>MC-OHS</td><td>MC-OHS</td><td>Users</td><td>Users</td><td>Videocassette</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>154</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRCL</td><td>HR-HRCL</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>132</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRHS</td><td>HR-HRHS</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>136</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRHS</td><td>HR-HRHS</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>169</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DALLES</td><td>WC-DALLES</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>170</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DALLES</td><td>WC-DALLES</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>173</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DALLES</td><td>WC-DALLES</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>179</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>183</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>189</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-SWCL</td><td>WC-SWCL</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>188</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-SWCL</td><td>WC-SWCL</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>192</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-SWCL</td><td>WC-SWCL</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>193</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-SWCL</td><td>WC-SWCL</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>197</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-PLANE</td><td>WC-PLANE</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>201</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-PLANE</td><td>WC-PLANE</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>206</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>SC-SCPS</td><td>SC-SCPS</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>210</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>SC-SCPS</td><td>SC-SCPS</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>202</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-PLANE</td><td>WC-PLANE</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>211</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>SC-SCPS</td><td>SC-SCPS</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Museum Passes</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>138</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>LIMITED - 2 CKO</td><td>LIMITED - 2 CKO</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>2</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>180</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>141</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-CLL</td><td>HR-CLL</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>145</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-CLL</td><td>HR-CLL</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>160</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-PCL</td><td>HR-PCL</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Equipment</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>150</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRCL</td><td>HR-HRCL</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>159</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-PCL</td><td>HR-PCL</td><td>PATRON</td><td>PATRON</td><td>Equipment</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>163</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-PCL</td><td>HR-PCL</td><td>PATRON</td><td>PATRON</td><td>Museum Passes</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>281</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>PATRON</td><td>PATRON</td><td>Diskette</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>285</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>PATRON</td><td>PATRON</td><td>Kit</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>287</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>PATRON</td><td>PATRON</td><td>Periodical</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>300</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-PLANE</td><td>WC-PLANE</td><td>PATRON</td><td>PATRON</td><td>Kit</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>288</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>Staff</td><td>Staff</td><td>Periodical</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>350</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRHS</td><td>HR-HRHS</td><td>Users</td><td>Users</td><td>DVD</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>348</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRHS</td><td>HR-HRHS</td><td>Users</td><td>Users</td><td>Memory Stick</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>343</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRHS</td><td>HR-HRHS</td><td>Staff</td><td>Staff</td><td>Memory Stick</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>139</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>&nbsp;</td><td>SAGE</td><td>Users</td><td>Users</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>209</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>SC-SCPS</td><td>SC-SCPS</td><td>STAFF & FACULTY</td><td>STAFF & FACULTY</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>171</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DALLES</td><td>WC-DALLES</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>181</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-DUFUR</td><td>WC-DUFUR</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>190</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-SWCL</td><td>WC-SWCL</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>199</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>WC-PLANE</td><td>WC-PLANE</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>208</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>SC-SCPS</td><td>SC-SCPS</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>148</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-CLL</td><td>HR-CLL</td><td>Staff</td><td>Staff</td><td>Ephemera</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>156</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-HRCL</td><td>HR-HRCL</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>f</td><td>f</td><td>t</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>167</td><td>&nbsp;</td><td>SAGE</td><td>&nbsp;</td><td>HR-PCL</td><td>HR-PCL</td><td>PATRON</td><td>PATRON</td><td>Ephemera</td><td>t</td><td>f</td><td>f</td><td>1</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>3</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>4</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL-HA</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>5</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL-HF</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>6</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL-HU</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>7</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL-RC</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>8</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL-SU</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>10</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BMCC</td><td>BMCC</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>12</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BMCC</td><td>BMCC</td><td>Users</td><td>Users</td><td>Hourly Reserves</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>13</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BMCC</td><td>BMCC</td><td>Users</td><td>Users</td><td>Daily Reserves</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>14</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BMCC</td><td>BMCC</td><td>Users</td><td>Users</td><td>Pamphlet</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>15</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BMCC</td><td>BMCC</td><td>Users</td><td>Users</td><td>Periodical</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>16</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BMCC</td><td>BMCC</td><td>Users</td><td>Users</td><td>Music CD</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>18</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>CGCC</td><td>CGCC</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>19</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>CGCC</td><td>CGCC</td><td>Users</td><td>Users</td><td>Hourly Reserves</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>20</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>CGCC</td><td>CGCC</td><td>Users</td><td>Users</td><td>Daily Reserves</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>23</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>GC-GCL</td><td>GC-GCL</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>24</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>GC-GCL</td><td>GC-GCL</td><td>Users</td><td>Users</td><td>Computer/Laptop</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>29</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-CV</td><td>LC-CV</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>31</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-LK</td><td>LC-LK</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>33</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-PA</td><td>LC-PA</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>35</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>LC-SL</td><td>LC-SL</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>2</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>BCLDIST</td><td>BCL-BKM</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>38</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>MC-NYSSA</td><td>MC-NYSSA</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>44</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>MC-OHS</td><td>MC-OHS</td><td>Users</td><td>Users</td><td>Periodical</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>47</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>MC-VHS</td><td>MC-VHS</td><td>Users</td><td>Users</td><td>Periodical</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>50</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>OTLD-BRD</td><td>OTLD-BRD</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>52</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>OTLD-HEP</td><td>OTLD-HEP</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>54</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>OTLD-IR</td><td>OTLD-IR</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>56</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>PIERCE</td><td>PIERCE</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>60</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>PIERCE</td><td>PIERCE</td><td>Users</td><td>Users</td><td>Hourly Reserves</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>61</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>PIERCE</td><td>PIERCE</td><td>Users</td><td>Users</td><td>Daily Reserves</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>70</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>UM-HPL</td><td>UM-HPL</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>73</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>UM-MF</td><td>UM-MF</td><td>Users</td><td>Users</td><td>Computer/Laptop</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>75</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>UM-PEN</td><td>UM-PEN</td><td>Users</td><td>Users</td><td>Equipment</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>79</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>UM-UPL</td><td>UM-UPL</td><td>Users</td><td>Users</td><td>Computer/Laptop</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>43</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>MC-OHS</td><td>MC-OHS</td><td>Users</td><td>Users</td><td>DVD</td><td>f</td><td>f</td><td>f</td><td>&nbsp;</td><td>0</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>518</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>Staff</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>511</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>STUDENT - ACADEMIC</td><td>STUDENT - ACADEMIC</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>100</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>513</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>Users</td><td>Users</td><td>Book Club Kits</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>1</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>536</td><td>&nbsp;</td><td>&nbsp;</td><td>UM-HPL</td><td>UM-HPL</td><td>UM-HPL</td><td>Users</td><td>Users</td><td>Deposit Required</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>&nbsp;</td><td>f</td><td>f</td><td>f</td></tr>
 <tr><td>577</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>FULL PRIVILEGES</td><td>FULL PRIVILEGES</td><td>&nbsp;</td><td>f</td><td>t</td><td>f</td><td>&nbsp;</td><td>9</td><td>f</td><td>f</td><td>f</td></tr>
</table>
<br>

##Permissions List

<table class="tableizer-table">
<tr class="tableizer-firstrow"><th>Permission</th><th>Description</th></tr>
 <tr><td>ABORT_REMOTE_TRANSIT</td><td>Allow a user to abort a copy transit if the user is not at the transit source or dest</td></tr>
 <tr><td>ABORT_TRANSIT</td><td>Allow a user to abort a copy transit if the user is at the transit destination or source</td></tr>
 <tr><td>ABORT_TRANSIT_ON_LOST</td><td>Allows a user to abort a transit on a copy with status of LOST</td></tr>
 <tr><td>ABORT_TRANSIT_ON_MISSING</td><td>Allows a user to abort a transit on a copy with status of MISSING</td></tr>
 <tr><td>ACQ_ADD_LINEITEM_IDENTIFIER</td><td>When granted, newly added lineitem identifiers will propagate to linked bib records</td></tr>
 <tr><td>ACQ_INVOICE_REOPEN</td><td>Allows a user to reopen an Acquisitions invoice</td></tr>
 <tr><td>ACQ_SET_LINEITEM_IDENTIFIER</td><td>Allows staff to change the lineitem identifier</td></tr>
 <tr><td>ACQ_XFER_MANUAL_DFUND_AMOUNT</td><td>Allow a user to transfer different amounts of money out of one fund and into another</td></tr>
 <tr><td>ACTOR_USER_DELETE_OPEN_XACTS.override</td><td>This override allows the ability to delete patrons who have open transactions on their record. DELETE_USER_XACTS.override does not seem to work.</td></tr>
 <tr><td>ADMIN_ACQ_CANCEL_CAUSE</td><td>Allow a user to create/update/delete reasons for order cancellations</td></tr>
 <tr><td>ADMIN_ACQ_CLAIM</td><td>ADMIN_ACQ_CLAIM</td></tr>
 <tr><td>ADMIN_ACQ_CLAIM_EVENT_TYPE</td><td>ADMIN_ACQ_CLAIM_EVENT_TYPE</td></tr>
 <tr><td>ADMIN_ACQ_CLAIM_TYPE</td><td>ADMIN_ACQ_CLAIM_TYPE</td></tr>
 <tr><td>ADMIN_ACQ_DISTRIB_FORMULA</td><td>ADMIN_ACQ_DISTRIB_FORMULA</td></tr>
 <tr><td>ADMIN_ACQ_FISCAL_YEAR</td><td>ADMIN_ACQ_FISCAL_YEAR</td></tr>
 <tr><td>ADMIN_ACQ_FUND</td><td>Allow a user to create/view/update/delete a fund</td></tr>
 <tr><td>ADMIN_ACQ_FUND_ALLOCATION_PERCENT</td><td>ADMIN_ACQ_FUND_ALLOCATION_PERCENT</td></tr>
 <tr><td>ADMIN_ACQ_FUND_TAG</td><td>ADMIN_ACQ_FUND_TAG</td></tr>
 <tr><td>ADMIN_ACQ_LINEITEM_ALERT_TEXT</td><td>ADMIN_ACQ_LINEITEM_ALERT_TEXT</td></tr>
 <tr><td>ADMIN_ADDRESS_ALERT</td><td>Allows a user to create/retrieve/update/delete address alerts</td></tr>
 <tr><td>ADMIN_AGE_PROTECT_RULE</td><td>ADMIN_AGE_PROTECT_RULE</td></tr>
 <tr><td>ADMIN_ASSET_COPY_TEMPLATE</td><td>ADMIN_ASSET_COPY_TEMPLATE</td></tr>
 <tr><td>ADMIN_BOOKING_RESERVATION</td><td>Enables the user to create/update/delete booking reservations</td></tr>
 <tr><td>ADMIN_BOOKING_RESERVATION_ATTR_MAP</td><td>ADMIN_BOOKING_RESERVATION_ATTR_MAP</td></tr>
 <tr><td>ADMIN_BOOKING_RESERVATION_ATTR_VALUE_MAP</td><td>Enables the user to create/update/delete booking reservation attribute value maps</td></tr>
 <tr><td>ADMIN_BOOKING_RESOURCE</td><td>Enables the user to create/update/delete booking resources</td></tr>
 <tr><td>ADMIN_BOOKING_RESOURCE_ATTR</td><td>Enables the user to create/update/delete booking resource attributes</td></tr>
 <tr><td>ADMIN_BOOKING_RESOURCE_ATTR_MAP</td><td>Enables the user to create/update/delete booking resource attribute maps</td></tr>
 <tr><td>ADMIN_BOOKING_RESOURCE_ATTR_VALUE</td><td>Enables the user to create/update/delete booking resource attribute values</td></tr>
 <tr><td>ADMIN_BOOKING_RESOURCE_TYPE</td><td>Enables the user to create/update/delete booking resource types</td></tr>
 <tr><td>ADMIN_CIRC_MATRIX_MATCHPOINT</td><td>ADMIN_CIRC_MATRIX_MATCHPOINT</td></tr>
 <tr><td>ADMIN_CIRC_MOD</td><td>ADMIN_CIRC_MOD</td></tr>
 <tr><td>ADMIN_CLAIM_POLICY</td><td>ADMIN_CLAIM_POLICY</td></tr>
 <tr><td>ADMIN_CODED_VALUE</td><td>Create/Update/Delete SVF Record Attribute Coded Value Map</td></tr>
 <tr><td>ADMIN_CONFIG_REMOTE_ACCOUNT</td><td>ADMIN_CONFIG_REMOTE_ACCOUNT</td></tr>
 <tr><td>ADMIN_COPY_LOCATION_GROUP</td><td>Allows a user to create/retrieve/update/delete copy location groups</td></tr>
 <tr><td>ADMIN_COPY_LOCATION_ORDER</td><td>Allow a user to create/view/update/delete a copy location order</td></tr>
 <tr><td>ADMIN_CREDIT_CARD_PROCESSING</td><td>Update org unit settings related to credit card processing</td></tr>
 <tr><td>ADMIN_CURRENCY_TYPE</td><td>Allow a user to create/view/update/delete a currency_type</td></tr>
 <tr><td>ADMIN_FIELD_DOC</td><td>ADMIN_FIELD_DOC</td></tr>
 <tr><td>ADMIN_FLOAT_GROUPS</td><td>Allows administration of floating groups</td></tr>
 <tr><td>ADMIN_FUND</td><td>(Deprecated) Allow a user to create/view/update/delete a fund</td></tr>
 <tr><td>ADMIN_FUNDING_SOURCE</td><td>Allow a user to create/view/update/delete a funding source</td></tr>
 <tr><td>ADMIN_GLOBAL_FLAG</td><td>ADMIN_GLOBAL_FLAG</td></tr>
 <tr><td>ADMIN_GROUP_PENALTY_THRESHOLD</td><td>ADMIN_GROUP_PENALTY_THRESHOLD</td></tr>
 <tr><td>ADMIN_HOLD_CANCEL_CAUSE</td><td>ADMIN_HOLD_CANCEL_CAUSE</td></tr>
 <tr><td>ADMIN_HOLD_CAPTURE_SORT</td><td>Allows a user to make changes to best-hold selection sort order</td></tr>
 <tr><td>ADMIN_HOLD_MATRIX_MATCHPOINT</td><td>ADMIN_HOLD_MATRIX_MATCHPOINT</td></tr>
 <tr><td>ADMIN_IDENT_TYPE</td><td>ADMIN_IDENT_TYPE</td></tr>
 <tr><td>ADMIN_IMPORT_ITEM_ATTR_DEF</td><td>ADMIN_IMPORT_ITEM_ATTR_DEF</td></tr>
 <tr><td>ADMIN_IMPORT_MATCH_SET</td><td>Allows a user to create/retrieve/update/delete vandelay match sets</td></tr>
 <tr><td>ADMIN_INDEX_NORMALIZER</td><td>ADMIN_INDEX_NORMALIZER</td></tr>
 <tr><td>ADMIN_INVOICE</td><td>ADMIN_INVOICE</td></tr>
 <tr><td>ADMIN_INVOICE_METHOD</td><td>ADMIN_INVOICE_METHOD</td></tr>
 <tr><td>ADMIN_INVOICE_PAYMENT_METHOD</td><td>ADMIN_INVOICE_PAYMENT_METHOD</td></tr>
 <tr><td>ADMIN_LINEITEM_MARC_ATTR_DEF</td><td>ADMIN_LINEITEM_MARC_ATTR_DEF</td></tr>
 <tr><td>ADMIN_MARC_CODE</td><td>ADMIN_MARC_CODE</td></tr>
 <tr><td>ADMIN_MAX_FINE_RULE</td><td>ADMIN_MAX_FINE_RULE</td></tr>
 <tr><td>ADMIN_MERGE_PROFILE</td><td>ADMIN_MERGE_PROFILE</td></tr>
 <tr><td>ADMIN_ORG_UNIT_CUSTOM_TREE</td><td>User may update custom org unit trees</td></tr>
 <tr><td>ADMIN_ORG_UNIT_SETTING_TYPE</td><td>ADMIN_ORG_UNIT_SETTING_TYPE</td></tr>
 <tr><td>ADMIN_PROVIDER</td><td>Allow a user to create/view/update/delete a provider</td></tr>
 <tr><td>ADMIN_PROXIMITY_ADJUSTMENT</td><td>So that we can edit Org Unit Proximities. Seemed to have been missing.</td></tr>
 <tr><td>ADMIN_RECURRING_FINE_RULE</td><td>ADMIN_RECURRING_FINE_RULE</td></tr>
 <tr><td>ADMIN_SEARCH_FILTER_GROUP</td><td>Allows staff to manage search filter groups and entries</td></tr>
 <tr><td>ADMIN_SERIAL_CAPTION_PATTERN</td><td>Create/update/delete serial caption and pattern objects</td></tr>
 <tr><td>ADMIN_SERIAL_DISTRIBUTION</td><td>Create/update/delete serial distribution objects</td></tr>
 <tr><td>ADMIN_SERIAL_ITEM</td><td>Create/Retrieve/Update/Delete Serial Item</td></tr>
 <tr><td>ADMIN_SERIAL_STREAM</td><td>Create/update/delete serial stream objects</td></tr>
 <tr><td>ADMIN_SERIAL_SUBSCRIPTION</td><td>Create/update/delete serial subscription objects</td></tr>
 <tr><td>ADMIN_SERVER_ADDON_FOR_WORKSTATION</td><td>Allows a user to specify which Server Add-ons get invoked at the current workstation</td></tr>
 <tr><td>ADMIN_SMS_CARRIER</td><td>Allows a user to add/create/delete SMS Carrier entries.</td></tr>
 <tr><td>ADMIN_STANDING_PENALTY</td><td>ADMIN_STANDING_PENALTY</td></tr>
 <tr><td>ADMIN_SURVEY</td><td>ADMIN_SURVEY</td></tr>
 <tr><td>ADMIN_SVF</td><td>Create/Update/Delete SVF Record Attribute Defintion</td></tr>
 <tr><td>ADMIN_TOOLBAR</td><td>Allows a user to create, edit, and delete custom toolbars</td></tr>
 <tr><td>ADMIN_TOOLBAR_FOR_ORG</td><td>Allows a user to create, edit, and delete custom toolbars for org units</td></tr>
 <tr><td>ADMIN_TOOLBAR_FOR_USER</td><td>Allows a user to create, edit, and delete custom toolbars for users</td></tr>
 <tr><td>ADMIN_TOOLBAR_FOR_WORKSTATION</td><td>Allows a user to create, edit, and delete custom toolbars for workstations</td></tr>
 <tr><td>ADMIN_TRIGGER_CLEANUP</td><td>Allow a user to create, delete, and update trigger cleanup entries</td></tr>
 <tr><td>ADMIN_TRIGGER_EVENT_DEF</td><td>Allow a user to administer trigger event definitions</td></tr>
 <tr><td>ADMIN_TRIGGER_HOOK</td><td>Allow a user to create, update, and delete trigger hooks</td></tr>
 <tr><td>ADMIN_TRIGGER_REACTOR</td><td>Allow a user to create, update, and delete trigger reactors</td></tr>
 <tr><td>ADMIN_TRIGGER_TEMPLATE_OUTPUT</td><td>Allow a user to delete trigger template output</td></tr>
 <tr><td>ADMIN_TRIGGER_VALIDATOR</td><td>Allow a user to create, update, and delete trigger validators</td></tr>
 <tr><td>ADMIN_USER_ACTIVITY_TYPE</td><td>Allows a user to create/retrieve/update/delete user activity types</td></tr>
 <tr><td>ADMIN_USER_REQUEST_TYPE</td><td>ADMIN_USER_REQUEST_TYPE</td></tr>
 <tr><td>ADMIN_USER_SETTING_GROUP</td><td>ADMIN_USER_SETTING_GROUP</td></tr>
 <tr><td>ADMIN_USER_SETTING_TYPE</td><td>ADMIN_USER_SETTING_TYPE</td></tr>
 <tr><td>ADMIN_Z3950_SOURCE</td><td>ADMIN_Z3950_SOURCE</td></tr>
 <tr><td>ALLOW_ALT_TCN</td><td>Allows staff to import a record using an alternate TCN to avoid conflicts</td></tr>
 <tr><td>ASSIGN_GROUP_PERM</td><td>ASSIGN_GROUP_PERM</td></tr>
 <tr><td>ASSIGN_WORK_ORG_UNIT</td><td>Allow a staff member to define where another staff member has their permissions</td></tr>
 <tr><td>BAR_PATRON</td><td>Allow a user to bar a patron</td></tr>
 <tr><td>CANCEL_HOLDS</td><td>Allow a user to cancel holds</td></tr>
 <tr><td>CAPTURE_RESERVATION</td><td>Allows a user to capture booking reservations</td></tr>
 <tr><td>CHECKIN_BYPASS_HOLD_FULFILL</td><td>* no longer applicable</td></tr>
 <tr><td>CIRC_CLAIMS_RETURNED.override</td><td>Allow a user to check in or check out an item that has a status of 'claims returned'</td></tr>
 <tr><td>CIRC_EXCEEDS_COPY_RANGE.override</td><td>Allow staff to override circulation copy range failure</td></tr>
 <tr><td>CIRC_OVERRIDE_DUE_DATE</td><td>Allow a user to change the due date on an item to any date</td></tr>
 <tr><td>CIRC_PERMIT_OVERRIDE</td><td>Allow a user to bypass the circulation permit call for check out</td></tr>
 <tr><td>COPY_ALERT_MESSAGE.override</td><td>Allow a user to check in/out an item that has an alert message</td></tr>
 <tr><td>COPY_BAD_STATUS.override</td><td>Allow a user to check out an item in a non-circulatable status</td></tr>
 <tr><td>COPY_CHECKIN</td><td>Allow a user to check in a copy</td></tr>
 <tr><td>COPY_CHECKOUT</td><td>Allow a user to check out a copy</td></tr>
 <tr><td>COPY_CIRC_NOT_ALLOWED.override</td><td>Allow a user to checkout an item that is marked as non-circ</td></tr>
 <tr><td>COPY_DELETE_WARNING.override</td><td>Allow a user to override warnings about deleting copies in problematic situations.</td></tr>
 <tr><td>COPY_HOLDS</td><td>Allow a user to place a hold on a specific copy</td></tr>
 <tr><td>COPY_HOLDS_FORCE</td><td>Allow a user to place a force hold on a specific copy</td></tr>
 <tr><td>COPY_HOLDS_RECALL</td><td>Allow a user to place a cataloging recall on a specific copy</td></tr>
 <tr><td>COPY_IS_REFERENCE.override</td><td>Allow a user to override the copy_is_reference event</td></tr>
 <tr><td>COPY_NEEDED_FOR_HOLD.override</td><td>Allow a user to force renewal of an item that could fulfill a hold request</td></tr>
 <tr><td>COPY_NOT_AVAILABLE.override</td><td>Allow staff to force checkout of Missing/Lost type items</td></tr>
 <tr><td>COPY_STATUS_LONGOVERDUE.override</td><td>Allows the user to check-in long-overdue items, prompting long-overdue check-in processing</td></tr>
 <tr><td>COPY_STATUS_LOST.override</td><td>Allow a user to remove the lost status from a copy</td></tr>
 <tr><td>COPY_STATUS_MISSING.override</td><td>Allow a user to change the missing status on a copy</td></tr>
 <tr><td>COPY_TRANSIT_RECEIVE</td><td>Allow a user to close out a transit on a copy</td></tr>
 <tr><td>CREATE_ACQ_FUNDING_SOURCE</td><td>CREATE_ACQ_FUNDING_SOURCE</td></tr>
 <tr><td>CREATE_AUDIENCE</td><td>CREATE_AUDIENCE</td></tr>
 <tr><td>CREATE_AUTHORITY_IMPORT_IMPORT_FIELD_DEF</td><td>CREATE_AUTHORITY_IMPORT_IMPORT_FIELD_DEF</td></tr>
 <tr><td>CREATE_AUTHORITY_IMPORT_QUEUE</td><td>CREATE_AUTHORITY_IMPORT_QUEUE</td></tr>
 <tr><td>CREATE_AUTHORITY_RECORD_NOTE</td><td>CREATE_AUTHORITY_RECORD_NOTE</td></tr>
 <tr><td>CREATE_BIBLIO_FINGERPRINT</td><td>CREATE_BIBLIO_FINGERPRINT</td></tr>
 <tr><td>CREATE_BIB_BTYPE</td><td>CREATE_BIB_BTYPE</td></tr>
 <tr><td>CREATE_BIB_IMPORT_FIELD_DEF</td><td>CREATE_BIB_IMPORT_FIELD_DEF</td></tr>
 <tr><td>CREATE_BIB_IMPORT_QUEUE</td><td>CREATE_BIB_IMPORT_QUEUE</td></tr>
 <tr><td>CREATE_BIB_LEVEL</td><td>CREATE_BIB_LEVEL</td></tr>
 <tr><td>CREATE_BIB_PTYPE</td><td>Create Bibliographic Record Peer Type</td></tr>
 <tr><td>CREATE_BIB_SOURCE</td><td>CREATE_BIB_SOURCE</td></tr>
 <tr><td>CREATE_BILL</td><td>Allow a user to create a new bill on a transaction</td></tr>
 <tr><td>CREATE_BILLING_TYPE</td><td>CREATE_BILLING_TYPE</td></tr>
 <tr><td>CREATE_CIRC_DURATION</td><td>CREATE_CIRC_DURATION</td></tr>
 <tr><td>CREATE_CIRC_MOD</td><td>CREATE_CIRC_MOD</td></tr>
 <tr><td>CREATE_CN_BTYPE</td><td>CREATE_CN_BTYPE</td></tr>
 <tr><td>CREATE_CONTAINER</td><td>Allow a user to create a new container for another user</td></tr>
 <tr><td>CREATE_CONTAINER_ITEM</td><td>Allow a user to create a container item for another user</td></tr>
 <tr><td>CREATE_COPY</td><td>Allow a user to create a new copy object</td></tr>
 <tr><td>CREATE_COPY_BTYPE</td><td>CREATE_COPY_BTYPE</td></tr>
 <tr><td>CREATE_COPY_LOCATION</td><td>Allow a user to create a new copy location</td></tr>
 <tr><td>CREATE_COPY_NOTE</td><td>Allow a user to create a new copy note</td></tr>
 <tr><td>CREATE_COPY_STATUS</td><td>CREATE_COPY_STATUS</td></tr>
 <tr><td>CREATE_COPY_STAT_CAT</td><td>User may create a copy statistical category</td></tr>
 <tr><td>CREATE_COPY_STAT_CAT_ENTRY</td><td>User may create an entry in a copy statistical category</td></tr>
 <tr><td>CREATE_COPY_STAT_CAT_ENTRY_MAP</td><td>User may link a copy to an entry in a statistical category</td></tr>
 <tr><td>CREATE_COPY_TRANSIT</td><td>Allow a user to create a transit_copy object for transiting a copy</td></tr>
 <tr><td>CREATE_DUPLICATE_HOLDS</td><td>Allow a user to create duplicate holds (two or more holds on the same title)</td></tr>
 <tr><td>CREATE_FUND</td><td>Allow a user to create a new fund</td></tr>
 <tr><td>CREATE_FUNDING_SOURCE</td><td>Allow a user to create a new funding source</td></tr>
 <tr><td>CREATE_FUND_ALLOCATION</td><td>Allow a user to create a new fund allocation</td></tr>
 <tr><td>CREATE_HOLD_NOTIFICATION</td><td>Allow a user to create new hold notifications</td></tr>
 <tr><td>CREATE_HOURS_OF_OPERATION</td><td>CREATE_HOURS_OF_OPERATION</td></tr>
 <tr><td>CREATE_IMPORT_ITEM</td><td>CREATE_IMPORT_ITEM</td></tr>
 <tr><td>CREATE_IMPORT_ITEM_ATTR_DEF</td><td>CREATE_IMPORT_ITEM_ATTR_DEF</td></tr>
 <tr><td>CREATE_IMPORT_TRASH_FIELD</td><td>CREATE_IMPORT_TRASH_FIELD</td></tr>
 <tr><td>CREATE_INVOICE</td><td>CREATE_INVOICE</td></tr>
 <tr><td>CREATE_INVOICE_ITEM_TYPE</td><td>CREATE_INVOICE_ITEM_TYPE</td></tr>
 <tr><td>CREATE_INVOICE_METHOD</td><td>CREATE_INVOICE_METHOD</td></tr>
 <tr><td>CREATE_IN_HOUSE_USE</td><td>Allow a user to create a new in-house-use </td></tr>
 <tr><td>CREATE_ITEM_FORM</td><td>CREATE_ITEM_FORM</td></tr>
 <tr><td>CREATE_ITEM_TYPE</td><td>CREATE_ITEM_TYPE</td></tr>
 <tr><td>CREATE_LANGUAGE</td><td>CREATE_LANGUAGE</td></tr>
 <tr><td>CREATE_LASSO</td><td>CREATE_LASSO</td></tr>
 <tr><td>CREATE_LASSO_MAP</td><td>CREATE_LASSO_MAP</td></tr>
 <tr><td>CREATE_LIT_FORM</td><td>CREATE_LIT_FORM</td></tr>
 <tr><td>CREATE_LOCALE</td><td>CREATE_LOCALE</td></tr>
 <tr><td>CREATE_MARC</td><td>Allow a user to create new MARC records</td></tr>
 <tr><td>CREATE_MARC_CODE</td><td>CREATE_MARC_CODE</td></tr>
 <tr><td>CREATE_MERGE_PROFILE</td><td>CREATE_MERGE_PROFILE</td></tr>
 <tr><td>CREATE_METABIB_CLASS</td><td>CREATE_METABIB_CLASS</td></tr>
 <tr><td>CREATE_METABIB_FIELD</td><td>CREATE_METABIB_FIELD</td></tr>
 <tr><td>CREATE_METABIB_SEARCH_ALIAS</td><td>CREATE_METABIB_SEARCH_ALIAS</td></tr>
 <tr><td>CREATE_MFHD_RECORD</td><td>Allows a user to create a new MFHD record</td></tr>
 <tr><td>CREATE_MONOGRAPH_PART</td><td>Create monograph part definition.</td></tr>
 <tr><td>CREATE_MY_CONTAINER</td><td>Allow a user to create a container for themselves</td></tr>
 <tr><td>CREATE_NET_ACCESS_LEVEL</td><td>CREATE_NET_ACCESS_LEVEL</td></tr>
 <tr><td>CREATE_NON_CAT_TYPE</td><td>Allow a user to create a new non-cataloged item type</td></tr>
 <tr><td>CREATE_ORG_ADDRESS</td><td>CREATE_ORG_ADDRESS</td></tr>
 <tr><td>CREATE_ORG_TYPE</td><td>CREATE_ORG_TYPE</td></tr>
 <tr><td>CREATE_ORG_UNIT</td><td>CREATE_ORG_UNIT</td></tr>
 <tr><td>CREATE_ORG_UNIT_CLOSING</td><td>CREATE_ORG_UNIT_CLOSING</td></tr>
 <tr><td>CREATE_PATRON_STAT_CAT</td><td>User may create a new patron statistical category</td></tr>
 <tr><td>CREATE_PATRON_STAT_CAT_ENTRY</td><td>User may create an entry in a patron statistical category</td></tr>
 <tr><td>CREATE_PATRON_STAT_CAT_ENTRY_DEFAULT</td><td>User may set a default entry in a patron statistical category</td></tr>
 <tr><td>CREATE_PATRON_STAT_CAT_ENTRY_MAP</td><td>User may link another user to an entry in a statistical category</td></tr>
 <tr><td>CREATE_PAYMENT</td><td>Allow a user to record payments in the Billing Interface</td></tr>
 <tr><td>CREATE_PERM</td><td>CREATE_PERM</td></tr>
 <tr><td>CREATE_PICKLIST</td><td>Allows a user to create a picklist</td></tr>
 <tr><td>CREATE_PROVIDER</td><td>Allow a user to create a new provider</td></tr>
 <tr><td>CREATE_PURCHASE_ORDER</td><td>Allows a user to create a purchase order</td></tr>
 <tr><td>CREATE_PURCHASE_REQUEST</td><td>Create User Purchase Request</td></tr>
 <tr><td>CREATE_RELEVANCE_ADJUSTMENT</td><td>CREATE_RELEVANCE_ADJUSTMENT</td></tr>
 <tr><td>CREATE_REPORT_TEMPLATE</td><td>Allows a user to create report templates</td></tr>
 <tr><td>CREATE_SURVEY</td><td>CREATE_SURVEY</td></tr>
 <tr><td>CREATE_TITLE_NOTE</td><td>Allow a user to create a new title note</td></tr>
 <tr><td>CREATE_TRANSACTION</td><td>Allow a user to create a new billable transaction</td></tr>
 <tr><td>CREATE_TRANSIT</td><td>Allow a user to place an item in transit</td></tr>
 <tr><td>CREATE_TRANSLATION</td><td>CREATE_TRANSLATION</td></tr>
 <tr><td>CREATE_TRIGGER_CLEANUP</td><td>Allow a user to create trigger cleanup entries</td></tr>
 <tr><td>CREATE_TRIGGER_EVENT_DEF</td><td>Allow a user to create trigger event definitions</td></tr>
 <tr><td>CREATE_TRIGGER_HOOK</td><td>Allow a user to create trigger hooks</td></tr>
 <tr><td>CREATE_TRIGGER_REACTOR</td><td>Allow a user to create trigger reactors</td></tr>
 <tr><td>CREATE_TRIGGER_VALIDATOR</td><td>Allow a user to create trigger validators</td></tr>
 <tr><td>CREATE_USER</td><td>Allow a user to create another user</td></tr>
 <tr><td>CREATE_USER_BTYPE</td><td>CREATE_USER_BTYPE</td></tr>
 <tr><td>CREATE_USER_GROUP_LINK</td><td>Allow a user to add other users to permission groups</td></tr>
 <tr><td>CREATE_VOLUME</td><td>Allow a user to create a volume</td></tr>
 <tr><td>CREATE_VOLUME_NOTE</td><td>Allow a user to create a new volume note</td></tr>
 <tr><td>CREATE_VOLUME_PREFIX</td><td>Create prefix label definition.</td></tr>
 <tr><td>CREATE_VOLUME_SUFFIX</td><td>Create suffix label definition.</td></tr>
 <tr><td>CREATE_VR_FORMAT</td><td>CREATE_VR_FORMAT</td></tr>
 <tr><td>CREATE_XML_TRANSFORM</td><td>CREATE_XML_TRANSFORM</td></tr>
 <tr><td>DEBUG_CLIENT</td><td>Allows a user to use debug functions in the staff client</td></tr>
 <tr><td>DELETE_ACQ_FUNDING_SOURCE</td><td>DELETE_ACQ_FUNDING_SOURCE</td></tr>
 <tr><td>DELETE_AUDIENCE</td><td>DELETE_AUDIENCE</td></tr>
 <tr><td>DELETE_AUTHORITY_IMPORT_IMPORT_FIELD_DEF</td><td>DELETE_AUTHORITY_IMPORT_IMPORT_FIELD_DEF</td></tr>
 <tr><td>DELETE_AUTHORITY_IMPORT_QUEUE</td><td>DELETE_AUTHORITY_IMPORT_QUEUE</td></tr>
 <tr><td>DELETE_AUTHORITY_RECORD_NOTE</td><td>DELETE_AUTHORITY_RECORD_NOTE</td></tr>
 <tr><td>DELETE_BIBLIO_FINGERPRINT</td><td>DELETE_BIBLIO_FINGERPRINT</td></tr>
 <tr><td>DELETE_BIB_BTYPE</td><td>DELETE_BIB_BTYPE</td></tr>
 <tr><td>DELETE_BIB_IMPORT_IMPORT_FIELD_DEF</td><td>DELETE_BIB_IMPORT_IMPORT_FIELD_DEF</td></tr>
 <tr><td>DELETE_BIB_IMPORT_QUEUE</td><td>DELETE_BIB_IMPORT_QUEUE</td></tr>
 <tr><td>DELETE_BIB_LEVEL</td><td>DELETE_BIB_LEVEL</td></tr>
 <tr><td>DELETE_BIB_PTYPE</td><td>Delete Bibliographic Record Peer Type</td></tr>
 <tr><td>DELETE_BIB_SOURCE</td><td>DELETE_BIB_SOURCE</td></tr>
 <tr><td>DELETE_BILLING_TYPE</td><td>DELETE_BILLING_TYPE</td></tr>
 <tr><td>DELETE_CIRC_DURATION</td><td>DELETE_CIRC_DURATION</td></tr>
 <tr><td>DELETE_CIRC_MOD</td><td>DELETE_CIRC_MOD</td></tr>
 <tr><td>DELETE_CN_BTYPE</td><td>DELETE_CN_BTYPE</td></tr>
 <tr><td>DELETE_CONTAINER</td><td>Allow a user to delete another user's container</td></tr>
 <tr><td>DELETE_CONTAINER_ITEM</td><td>Allow a user to delete an item out of another user's container</td></tr>
 <tr><td>DELETE_COPY</td><td>Allow a user to delete a copy</td></tr>
 <tr><td>DELETE_COPY_BTYPE</td><td>DELETE_COPY_BTYPE</td></tr>
 <tr><td>DELETE_COPY_LOCATION</td><td>Allow a user to delete a copy location</td></tr>
 <tr><td>DELETE_COPY_NOTE</td><td>Allow a user to delete another user's copy notes</td></tr>
 <tr><td>DELETE_COPY_STATUS</td><td>DELETE_COPY_STATUS</td></tr>
 <tr><td>DELETE_COPY_STAT_CAT</td><td>User may delete a copy statistical category</td></tr>
 <tr><td>DELETE_COPY_STAT_CAT_ENTRY</td><td>User may delete an entry from a copy statistical category</td></tr>
 <tr><td>DELETE_COPY_STAT_CAT_ENTRY_MAP</td><td>User may delete a copy statistical category entry map</td></tr>
 <tr><td>DELETE_FUND</td><td>Allow a user to delete a fund</td></tr>
 <tr><td>DELETE_FUNDING_SOURCE</td><td>Allow a user to delete a funding source</td></tr>
 <tr><td>DELETE_FUND_ALLOCATION</td><td>Allow a user to delete a fund allocation</td></tr>
 <tr><td>DELETE_HOLDS</td><td>* no longer applicable</td></tr>
 <tr><td>DELETE_HOURS_OF_OPERATION</td><td>DELETE_HOURS_OF_OPERATION</td></tr>
 <tr><td>DELETE_IMPORT_ITEM</td><td>DELETE_IMPORT_ITEM</td></tr>
 <tr><td>DELETE_IMPORT_ITEM_ATTR_DEF</td><td>DELETE_IMPORT_ITEM_ATTR_DEF</td></tr>
 <tr><td>DELETE_IMPORT_TRASH_FIELD</td><td>DELETE_IMPORT_TRASH_FIELD</td></tr>
 <tr><td>DELETE_INVOICE_ITEM_TYPE</td><td>DELETE_INVOICE_ITEM_TYPE</td></tr>
 <tr><td>DELETE_INVOICE_METHOD</td><td>DELETE_INVOICE_METHOD</td></tr>
 <tr><td>DELETE_ITEM_FORM</td><td>DELETE_ITEM_FORM</td></tr>
 <tr><td>DELETE_ITEM_TYPE</td><td>DELETE_ITEM_TYPE</td></tr>
 <tr><td>DELETE_LANGUAGE</td><td>DELETE_LANGUAGE</td></tr>
 <tr><td>DELETE_LASSO</td><td>DELETE_LASSO</td></tr>
 <tr><td>DELETE_LASSO_MAP</td><td>DELETE_LASSO_MAP</td></tr>
 <tr><td>DELETE_LIT_FORM</td><td>DELETE_LIT_FORM</td></tr>
 <tr><td>DELETE_LOCALE</td><td>DELETE_LOCALE</td></tr>
 <tr><td>DELETE_MARC_CODE</td><td>DELETE_MARC_CODE</td></tr>
 <tr><td>DELETE_MERGE_PROFILE</td><td>DELETE_MERGE_PROFILE</td></tr>
 <tr><td>DELETE_METABIB_CLASS</td><td>DELETE_METABIB_CLASS</td></tr>
 <tr><td>DELETE_METABIB_FIELD</td><td>DELETE_METABIB_FIELD</td></tr>
 <tr><td>DELETE_METABIB_SEARCH_ALIAS</td><td>DELETE_METABIB_SEARCH_ALIAS</td></tr>
 <tr><td>DELETE_MFHD_RECORD</td><td>Allows a user to delete an MFHD record</td></tr>
 <tr><td>DELETE_MONOGRAPH_PART</td><td>Delete monograph part definition.</td></tr>
 <tr><td>DELETE_NET_ACCESS_LEVEL</td><td>DELETE_NET_ACCESS_LEVEL</td></tr>
 <tr><td>DELETE_NON_CAT_TYPE</td><td>Allow a user to delete a non cataloged type</td></tr>
 <tr><td>DELETE_ORG_ADDRESS</td><td>DELETE_ORG_ADDRESS</td></tr>
 <tr><td>DELETE_ORG_TYPE</td><td>DELETE_ORG_TYPE</td></tr>
 <tr><td>DELETE_ORG_UNIT</td><td>DELETE_ORG_UNIT</td></tr>
 <tr><td>DELETE_ORG_UNIT_CLOSING</td><td>DELETE_ORG_UNIT_CLOSING</td></tr>
 <tr><td>DELETE_PATRON_STAT_CAT</td><td>User may delete a patron statistical category</td></tr>
 <tr><td>DELETE_PATRON_STAT_CAT_ENTRY</td><td>User may delete an entry from a patron statistical category</td></tr>
 <tr><td>DELETE_PATRON_STAT_CAT_ENTRY_DEFAULT</td><td>User may unset a default entry in a patron statistical category</td></tr>
 <tr><td>DELETE_PATRON_STAT_CAT_ENTRY_MAP</td><td>User may delete a patron statistical category entry map</td></tr>
 <tr><td>DELETE_PERM</td><td>DELETE_PERM</td></tr>
 <tr><td>DELETE_PROVIDER</td><td>Allow a user to delete a provider</td></tr>
 <tr><td>DELETE_RECORD</td><td>Allow a staff member to directly remove a bibliographic record</td></tr>
 <tr><td>DELETE_RELEVANCE_ADJUSTMENT</td><td>DELETE_RELEVANCE_ADJUSTMENT</td></tr>
 <tr><td>DELETE_SURVEY</td><td>DELETE_SURVEY</td></tr>
 <tr><td>DELETE_TITLE_NOTE</td><td>Allow a user to delete another user's title note</td></tr>
 <tr><td>DELETE_TRANSIT</td><td>DELETE_TRANSIT</td></tr>
 <tr><td>DELETE_TRANSLATION</td><td>DELETE_TRANSLATION</td></tr>
 <tr><td>DELETE_TRIGGER_CLEANUP</td><td>Allow a user to delete trigger cleanup entries</td></tr>
 <tr><td>DELETE_TRIGGER_EVENT_DEF</td><td>Allow a user to delete trigger event definitions</td></tr>
 <tr><td>DELETE_TRIGGER_HOOK</td><td>Allow a user to delete trigger hooks</td></tr>
 <tr><td>DELETE_TRIGGER_REACTOR</td><td>Allow a user to delete trigger reactors</td></tr>
 <tr><td>DELETE_TRIGGER_TEMPLATE_OUTPUT</td><td>Allow a user to delete trigger template output</td></tr>
 <tr><td>DELETE_TRIGGER_VALIDATOR</td><td>Allow a user to delete trigger validators</td></tr>
 <tr><td>DELETE_USER</td><td>Allow a user to mark a user as deleted</td></tr>
 <tr><td>DELETE_USER_BTYPE</td><td>DELETE_USER_BTYPE</td></tr>
 <tr><td>DELETE_USER_XACTS.override</td><td>&nbsp;</td></tr>
 <tr><td>DELETE_VOLUME</td><td>Allow a user to delete a volume</td></tr>
 <tr><td>DELETE_VOLUME_NOTE</td><td>Allow a user to delete another user's volume note</td></tr>
 <tr><td>DELETE_VOLUME_PREFIX</td><td>Delete prefix label definition.</td></tr>
 <tr><td>DELETE_VOLUME_SUFFIX</td><td>Delete suffix label definition.</td></tr>
 <tr><td>DELETE_VR_FORMAT</td><td>DELETE_VR_FORMAT</td></tr>
 <tr><td>DELETE_WORKSTATION</td><td>Allow a user to remove an existing workstation so a new one can replace it</td></tr>
 <tr><td>DELETE_XML_TRANSFORM</td><td>DELETE_XML_TRANSFORM</td></tr>
 <tr><td>EVERYTHING</td><td>EVERYTHING</td></tr>
 <tr><td>GENERAL_ACQ</td><td>Lowest level permission required to access the ACQ interface</td></tr>
 <tr><td>HOLD_EXISTS.override</td><td>Allow a user to place multiple holds on a single title</td></tr>
 <tr><td>HOLD_ITEM_CHECKED_OUT.override</td><td>Allows a user to place a hold on an item that they already have checked out</td></tr>
 <tr><td>HOLD_LOCAL_AVAIL_OVERRIDE</td><td>Allow a user to place a hold despite the availability of a local copy</td></tr>
 <tr><td>IMPORT_ACQ_LINEITEM_BIB_RECORD</td><td>Allows a user to import a bib record from the acq staging area (on-order record) into the ILS bib data set</td></tr>
 <tr><td>IMPORT_ACQ_LINEITEM_BIB_RECORD_UPLOAD</td><td>Allows a user to create new bibs directly from an ACQ MARC file upload</td></tr>
 <tr><td>IMPORT_AUTHORITY_MARC</td><td>Allows a user to create new authority records</td></tr>
 <tr><td>IMPORT_MARC</td><td>Allow a user to import a MARC record via the Z39.50 interface</td></tr>
 <tr><td>IMPORT_OVERLAY_COPY</td><td>Allows a user to overlay copy data in MARC import</td></tr>
 <tr><td>ISSUANCE_HOLDS</td><td>Allow a user to place holds on serials issuances</td></tr>
 <tr><td>ITEM_AGE_PROTECTED.override</td><td>Allow a user to place a hold on an age-protected item</td></tr>
 <tr><td>ITEM_DEPOSIT_PAID.override</td><td>ITEM_DEPOSIT_PAID.override</td></tr>
 <tr><td>ITEM_DEPOSIT_REQUIRED.override</td><td>ITEM_DEPOSIT_REQUIRED.override</td></tr>
 <tr><td>ITEM_ON_HOLDS_SHELF.override</td><td>Allow staff to override item on holds shelf failure</td></tr>
 <tr><td>MANAGE_CLAIM</td><td>MANAGE_CLAIM</td></tr>
 <tr><td>MANAGE_FUND</td><td>Allow a user to view/credit/debit a fund</td></tr>
 <tr><td>MANAGE_FUNDING_SOURCE</td><td>Allow a user to view/credit/debit a funding source</td></tr>
 <tr><td>MANAGE_PROVIDER</td><td>Allow a user to view and purchase from a provider</td></tr>
 <tr><td>MAP_MONOGRAPH_PART</td><td>Create/Update/Delete Copy Monograph Part Map</td></tr>
 <tr><td>MARK_BAD_DEBT</td><td>Allow a user to mark a transaction as bad (unrecoverable) debt</td></tr>
 <tr><td>MARK_ITEM_AVAILABLE</td><td>Allow a user to mark an item status as 'available'</td></tr>
 <tr><td>MARK_ITEM_BINDERY</td><td>Allow a user to mark an item status as 'bindery'</td></tr>
 <tr><td>MARK_ITEM_CHECKED_OUT</td><td>Allow a user to mark an item status as 'checked out'</td></tr>
 <tr><td>MARK_ITEM_ILL</td><td>Allow a user to mark an item status as 'inter-library loan'</td></tr>
 <tr><td>MARK_ITEM_IN_PROCESS</td><td>Allow a user to mark an item status as 'in process'</td></tr>
 <tr><td>MARK_ITEM_IN_TRANSIT</td><td>Allow a user to mark an item status as 'in transit'</td></tr>
 <tr><td>MARK_ITEM_LOST</td><td>Allow a user to mark an item status as 'lost'</td></tr>
 <tr><td>MARK_ITEM_MISSING</td><td>Allow a user to mark an item status as 'missing'</td></tr>
 <tr><td>MARK_ITEM_MISSING_PIECES</td><td>Allows the Mark Item Missing Pieces action.</td></tr>
 <tr><td>MARK_ITEM_ON_HOLDS_SHELF</td><td>Allow a user to mark an item status as 'on holds shelf'</td></tr>
 <tr><td>MARK_ITEM_ON_ORDER</td><td>Allow a user to mark an item status as 'on order'</td></tr>
 <tr><td>MARK_ITEM_RESHELVING</td><td>Allow a user to mark an item status as 'reshelving'</td></tr>
 <tr><td>MAX_RENEWALS_REACHED.override</td><td>Allow a user to renew an item past the maximum renewal count</td></tr>
 <tr><td>MERGE_AUTH_RECORDS</td><td>Allow a user to merge authority records together</td></tr>
 <tr><td>MERGE_BIB_RECORDS</td><td>MERGE_BIB_RECORDS</td></tr>
 <tr><td>MERGE_USERS</td><td>Allows user records to be merged</td></tr>
 <tr><td>MR_HOLDS</td><td>Allow a user to create a metarecord holds</td></tr>
 <tr><td>OFFLINE_EXECUTE</td><td>Allow a user to execute an offline script batch</td></tr>
 <tr><td>OFFLINE_UPLOAD</td><td>Allow a user to upload an offline script</td></tr>
 <tr><td>OFFLINE_VIEW</td><td>Allow a user to view uploaded offline script information</td></tr>
 <tr><td>OPAC_LOGIN</td><td>Allow a user to log in to the OPAC</td></tr>
 <tr><td>OVERRIDE_HOLD_HAS_LOCAL_COPY</td><td>Allow a user to override the circ.holds.hold_has_copy_at.block setting</td></tr>
 <tr><td>PATRON_EXCEEDS_CHECKOUT_COUNT.override</td><td>Allow staff to override checkout count failure</td></tr>
 <tr><td>PATRON_EXCEEDS_FINES.override</td><td>Allow staff to override fine amount checkout failure</td></tr>
 <tr><td>PATRON_EXCEEDS_OVERDUE_COUNT.override</td><td>Allow staff to override overdue count failure</td></tr>
 <tr><td>PERSISTENT_LOGIN</td><td>Allows a user to authenticate and get a long-lived session (length configured in opensrf.xml)</td></tr>
 <tr><td>PLACE_UNFILLABLE_HOLD</td><td>Allows a user to place a hold that cannot currently be filled.</td></tr>
 <tr><td>RECEIVE_PURCHASE_ORDER</td><td>Allows a user to mark a purchase order, lineitem, or individual copy as received</td></tr>
 <tr><td>RECEIVE_SERIAL</td><td>Receive serial items</td></tr>
 <tr><td>REGISTER_WORKSTATION</td><td>Allow a user to register a new workstation</td></tr>
 <tr><td>REMOTE_Z3950_QUERY</td><td>Allow a user to perform Z39.50 queries against remote servers</td></tr>
 <tr><td>REMOVE_GROUP_PERM</td><td>REMOVE_GROUP_PERM</td></tr>
 <tr><td>REMOVE_USER_GROUP_LINK</td><td>Allow a user to remove other users from permission groups</td></tr>
 <tr><td>RENEW_CIRC</td><td>Allow a user to renew items</td></tr>
 <tr><td>RENEW_HOLD_OVERRIDE</td><td>Allow a user to continue to renew an item even if it is required for a hold</td></tr>
 <tr><td>REQUEST_HOLDS</td><td>Allow a user to create holds for another user (if true, we still check to make sure they have permission to make the type of hold they are requesting, for example, COPY_HOLDS)</td></tr>
 <tr><td>REQUEST_HOLDS_OVERRIDE</td><td>* no longer applicable</td></tr>
 <tr><td>RETRIEVE_RESERVATION_PULL_LIST</td><td>Allows a user to retrieve a booking reservation pull list</td></tr>
 <tr><td>RUN_REPORTS</td><td>Allow a user to run reports</td></tr>
 <tr><td>SAVED_FILTER_DIALOG_FILTERS</td><td>Allows users to save and load sets of filters for filter dialogs, available in certain staff interfaces</td></tr>
 <tr><td>SET_CIRC_CLAIMS_RETURNED</td><td>Allow a user to mark an item as 'claims returned'</td></tr>
 <tr><td>SET_CIRC_CLAIMS_RETURNED.override</td><td>Allows staff to override the max claims returned value for a patron</td></tr>
 <tr><td>SET_CIRC_LONG_OVERDUE</td><td>Allows the user to mark a circulation as long-overdue</td></tr>
 <tr><td>SET_CIRC_LOST</td><td>Allow a user to mark an item as 'lost'</td></tr>
 <tr><td>SET_CIRC_MISSING</td><td>Allow a user to mark an item as 'missing'</td></tr>
 <tr><td>SHARE_REPORT_FOLDER</td><td>Allow a user to share report his own folders</td></tr>
 <tr><td>STAFF_LOGIN</td><td>Allow a user to log in to the staff client</td></tr>
 <tr><td>TITLE_HOLDS</td><td>Allow a user to place a hold at the title level</td></tr>
 <tr><td>TRANSIT_CHECKIN_INTERVAL_BLOCK.override</td><td>Allows a user to override the TRANSIT_CHECKIN_INTERVAL_BLOCK event</td></tr>
 <tr><td>TRANSIT_COPY</td><td>TRANSIT_COPY</td></tr>
 <tr><td>UNBAR_PATRON</td><td>Allow a user to un-bar a patron</td></tr>
 <tr><td>UPDATE_ACQ_FUNDING_SOURCE</td><td>UPDATE_ACQ_FUNDING_SOURCE</td></tr>
 <tr><td>UPDATE_AUDIENCE</td><td>UPDATE_AUDIENCE</td></tr>
 <tr><td>UPDATE_AUTHORITY_IMPORT_IMPORT_FIELD_DEF</td><td>UPDATE_AUTHORITY_IMPORT_IMPORT_FIELD_DEF</td></tr>
 <tr><td>UPDATE_AUTHORITY_IMPORT_QUEUE</td><td>UPDATE_AUTHORITY_IMPORT_QUEUE</td></tr>
 <tr><td>UPDATE_AUTHORITY_RECORD_NOTE</td><td>UPDATE_AUTHORITY_RECORD_NOTE</td></tr>
 <tr><td>UPDATE_BATCH_COPY</td><td>Allow a user to edit copies in batch</td></tr>
 <tr><td>UPDATE_BIBLIO_FINGERPRINT</td><td>UPDATE_BIBLIO_FINGERPRINT</td></tr>
 <tr><td>UPDATE_BIB_BTYPE</td><td>UPDATE_BIB_BTYPE</td></tr>
 <tr><td>UPDATE_BIB_IMPORT_IMPORT_FIELD_DEF</td><td>UPDATE_BIB_IMPORT_IMPORT_FIELD_DEF</td></tr>
 <tr><td>UPDATE_BIB_IMPORT_QUEUE</td><td>UPDATE_BIB_IMPORT_QUEUE</td></tr>
 <tr><td>UPDATE_BIB_LEVEL</td><td>UPDATE_BIB_LEVEL</td></tr>
 <tr><td>UPDATE_BIB_PTYPE</td><td>Update Bibliographic Record Peer Type</td></tr>
 <tr><td>UPDATE_BIB_SOURCE</td><td>UPDATE_BIB_SOURCE</td></tr>
 <tr><td>UPDATE_BILLING_TYPE</td><td>UPDATE_BILLING_TYPE</td></tr>
 <tr><td>UPDATE_BILL_NOTE</td><td>Allows staff to edit the note for a bill on a transaction</td></tr>
 <tr><td>UPDATE_CIRC_DURATION</td><td>UPDATE_CIRC_DURATION</td></tr>
 <tr><td>UPDATE_CIRC_MOD</td><td>UPDATE_CIRC_MOD</td></tr>
 <tr><td>UPDATE_CN_BTYPE</td><td>UPDATE_CN_BTYPE</td></tr>
 <tr><td>UPDATE_CONTAINER</td><td>Allow a user to update another user's container</td></tr>
 <tr><td>UPDATE_COPY</td><td>Allow a user to edit a copy</td></tr>
 <tr><td>UPDATE_COPY_BTYPE</td><td>UPDATE_COPY_BTYPE</td></tr>
 <tr><td>UPDATE_COPY_LOCATION</td><td>Allow a user to update a copy location</td></tr>
 <tr><td>UPDATE_COPY_NOTE</td><td>UPDATE_COPY_NOTE</td></tr>
 <tr><td>UPDATE_COPY_STATUS</td><td>UPDATE_COPY_STATUS</td></tr>
 <tr><td>UPDATE_COPY_STAT_CAT</td><td>User may update a copy statistical category</td></tr>
 <tr><td>UPDATE_COPY_STAT_CAT_ENTRY</td><td>User may update an entry in a copy statistical category</td></tr>
 <tr><td>UPDATE_FUND</td><td>Allow a user to update a fund</td></tr>
 <tr><td>UPDATE_FUNDING_SOURCE</td><td>Allow a user to update a funding source</td></tr>
 <tr><td>UPDATE_FUND_ALLOCATION</td><td>Allow a user to update a fund allocation</td></tr>
 <tr><td>UPDATE_GROUP_PERM</td><td>UPDATE_GROUP_PERM</td></tr>
 <tr><td>UPDATE_HOLD</td><td>Allow a user to update another user's hold</td></tr>
 <tr><td>UPDATE_HOLD_REQUEST_TIME</td><td>Allows editing of a hold's request time, and/or its Cut-in-line/Top-of-queue flag.</td></tr>
 <tr><td>UPDATE_HOURS_OF_OPERATION</td><td>UPDATE_HOURS_OF_OPERATION</td></tr>
 <tr><td>UPDATE_IMPORT_ITEM</td><td>UPDATE_IMPORT_ITEM</td></tr>
 <tr><td>UPDATE_IMPORT_ITEM_ATTR_DEF</td><td>UPDATE_IMPORT_ITEM_ATTR_DEF</td></tr>
 <tr><td>UPDATE_IMPORT_TRASH_FIELD</td><td>UPDATE_IMPORT_TRASH_FIELD</td></tr>
 <tr><td>UPDATE_INVOICE_ITEM_TYPE</td><td>UPDATE_INVOICE_ITEM_TYPE</td></tr>
 <tr><td>UPDATE_INVOICE_METHOD</td><td>UPDATE_INVOICE_METHOD</td></tr>
 <tr><td>UPDATE_ITEM_FORM</td><td>UPDATE_ITEM_FORM</td></tr>
 <tr><td>UPDATE_ITEM_TYPE</td><td>UPDATE_ITEM_TYPE</td></tr>
 <tr><td>UPDATE_LANGUAGE</td><td>UPDATE_LANGUAGE</td></tr>
 <tr><td>UPDATE_LASSO</td><td>UPDATE_LASSO</td></tr>
 <tr><td>UPDATE_LASSO_MAP</td><td>UPDATE_LASSO_MAP</td></tr>
 <tr><td>UPDATE_LIT_FORM</td><td>UPDATE_LIT_FORM</td></tr>
 <tr><td>UPDATE_LOCALE</td><td>UPDATE_LOCALE</td></tr>
 <tr><td>UPDATE_MARC</td><td>Allow a user to edit a MARC record</td></tr>
 <tr><td>UPDATE_MARC_CODE</td><td>UPDATE_MARC_CODE</td></tr>
 <tr><td>UPDATE_MERGE_PROFILE</td><td>UPDATE_MERGE_PROFILE</td></tr>
 <tr><td>UPDATE_METABIB_CLASS</td><td>UPDATE_METABIB_CLASS</td></tr>
 <tr><td>UPDATE_METABIB_FIELD</td><td>UPDATE_METABIB_FIELD</td></tr>
 <tr><td>UPDATE_METABIB_SEARCH_ALIAS</td><td>UPDATE_METABIB_SEARCH_ALIAS</td></tr>
 <tr><td>UPDATE_MFHD_RECORD</td><td>Allows a user to update an MFHD record</td></tr>
 <tr><td>UPDATE_MONOGRAPH_PART</td><td>Update monograph part definition.</td></tr>
 <tr><td>UPDATE_NET_ACCESS_LEVEL</td><td>UPDATE_NET_ACCESS_LEVEL</td></tr>
 <tr><td>UPDATE_NON_CAT_TYPE</td><td>Allow a user to update a non-cataloged item type</td></tr>
 <tr><td>UPDATE_ORG_ADDRESS</td><td>UPDATE_ORG_ADDRESS</td></tr>
 <tr><td>UPDATE_ORG_SETTING</td><td>Allow a user to update an organization unit setting</td></tr>
 <tr><td>UPDATE_ORG_TYPE</td><td>UPDATE_ORG_TYPE</td></tr>
 <tr><td>UPDATE_ORG_UNIT</td><td>Allow a user to change the settings for an organization unit</td></tr>
 <tr><td>UPDATE_ORG_UNIT_CLOSING</td><td>UPDATE_ORG_UNIT_CLOSING</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.auth.opac_timeout</td><td>UPDATE_ORG_UNIT_SETTING.auth.opac_timeout</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.auth.staff_timeout</td><td>UPDATE_ORG_UNIT_SETTING.auth.staff_timeout</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.cat.bib.alert_on_empty</td><td>UPDATE_ORG_UNIT_SETTING.cat.bib.alert_on_empty</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.cat.bib.keep_on_empty</td><td>UPDATE_ORG_UNIT_SETTING.cat.bib.keep_on_empty</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.cat.default_item_price</td><td>UPDATE_ORG_UNIT_SETTING.cat.default_item_price</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.block_renews_for_holds</td><td>UPDATE_ORG_UNIT_SETTING.circ.block_renews_for_holds</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.hold_boundary.hard</td><td>UPDATE_ORG_UNIT_SETTING.circ.hold_boundary.hard</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.hold_boundary.soft</td><td>UPDATE_ORG_UNIT_SETTING.circ.hold_boundary.soft</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.hold_expire_alert_interval</td><td>UPDATE_ORG_UNIT_SETTING.circ.hold_expire_alert_interval</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.hold_expire_interval</td><td>UPDATE_ORG_UNIT_SETTING.circ.hold_expire_interval</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.hold_stalling.soft</td><td>UPDATE_ORG_UNIT_SETTING.circ.hold_stalling.soft</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.item_checkout_history.max</td><td>UPDATE_ORG_UNIT_SETTING.circ.item_checkout_history.max</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.lost_materials_processing_fee</td><td>UPDATE_ORG_UNIT_SETTING.circ.lost_materials_processing_fee</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.reshelving_complete.interval</td><td>UPDATE_ORG_UNIT_SETTING.circ.reshelving_complete.interval</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.selfcheck.alert_on_checkout_event</td><td>UPDATE_ORG_UNIT_SETTING.circ.selfcheck.alert_on_checkout_event</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.selfcheck.patron_login_timeout</td><td>UPDATE_ORG_UNIT_SETTING.circ.selfcheck.patron_login_timeout</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.selfcheck.require_patron_password</td><td>UPDATE_ORG_UNIT_SETTING.circ.selfcheck.require_patron_password</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.circ.void_overdue_on_lost</td><td>UPDATE_ORG_UNIT_SETTING.circ.void_overdue_on_lost</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.credit.payments.allow</td><td>UPDATE_ORG_UNIT_SETTING.credit.payments.allow</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.global.juvenile_age_threshold</td><td>UPDATE_ORG_UNIT_SETTING.global.juvenile_age_threshold</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.global.password_regex</td><td>UPDATE_ORG_UNIT_SETTING.global.password_regex</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.opac.barcode_regex</td><td>UPDATE_ORG_UNIT_SETTING.opac.barcode_regex</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.org.bounced_emails</td><td>UPDATE_ORG_UNIT_SETTING.org.bounced_emails</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.patron.password.use_phone</td><td>UPDATE_ORG_UNIT_SETTING.patron.password.use_phone</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING.ui.hide_copy_editor_fields</td><td>Allows staff to edit displayed copy editor fields</td></tr>
 <tr><td>UPDATE_ORG_UNIT_SETTING_ALL</td><td>UPDATE_ORG_UNIT_SETTING_ALL</td></tr>
 <tr><td>UPDATE_PATRON_ACTIVE_CARD</td><td>Allows a user to manually adjust a patron's active cards</td></tr>
 <tr><td>UPDATE_PATRON_CLAIM_NEVER_CHECKED_OUT_COUNT</td><td>Allows staff to manually change a patron's claims never checkout out count</td></tr>
 <tr><td>UPDATE_PATRON_CLAIM_RETURN_COUNT</td><td>Allows staff to manually change a patron's claims returned count</td></tr>
 <tr><td>UPDATE_PATRON_COLLECTIONS_EXEMPT</td><td>Allows a user to indicate that a patron is exempt from collections processing</td></tr>
 <tr><td>UPDATE_PATRON_PRIMARY_CARD</td><td>Allows a user to manually adjust a patron's primary card</td></tr>
 <tr><td>UPDATE_PATRON_STAT_CAT</td><td>User may update a patron statistical category</td></tr>
 <tr><td>UPDATE_PATRON_STAT_CAT_ENTRY</td><td>User may update an entry in a patron statistical category</td></tr>
 <tr><td>UPDATE_PATRON_STAT_CAT_ENTRY_DEFAULT</td><td>User may reset a default entry in a patron statistical category</td></tr>
 <tr><td>UPDATE_PAYMENT_NOTE</td><td>Allows staff to edit the note for a payment on a transaction</td></tr>
 <tr><td>UPDATE_PERM</td><td>UPDATE_PERM</td></tr>
 <tr><td>UPDATE_PICKLIST</td><td>Allows update/re-use of an acquisitions pick/selection list.</td></tr>
 <tr><td>UPDATE_PICKUP_LIB_FROM_HOLDS_SHELF</td><td>UPDATE_PICKUP_LIB_FROM_HOLDS_SHELF</td></tr>
 <tr><td>UPDATE_PICKUP_LIB_FROM_TRANSIT</td><td>Allow a user to change the pickup and transit destination for a captured hold item already in transit</td></tr>
 <tr><td>UPDATE_PROVIDER</td><td>Allow a user to update a provider</td></tr>
 <tr><td>UPDATE_RECORD</td><td>UPDATE_RECORD</td></tr>
 <tr><td>UPDATE_RELEVANCE_ADJUSTMENT</td><td>UPDATE_RELEVANCE_ADJUSTMENT</td></tr>
 <tr><td>UPDATE_SURVEY</td><td>UPDATE_SURVEY</td></tr>
 <tr><td>UPDATE_TRANSIT</td><td>UPDATE_TRANSIT</td></tr>
 <tr><td>UPDATE_TRANSLATION</td><td>UPDATE_TRANSLATION</td></tr>
 <tr><td>UPDATE_TRIGGER_CLEANUP</td><td>Allow a user to update trigger cleanup entries</td></tr>
 <tr><td>UPDATE_TRIGGER_EVENT_DEF</td><td>Allow a user to update trigger event definitions</td></tr>
 <tr><td>UPDATE_TRIGGER_HOOK</td><td>Allow a user to update trigger hooks</td></tr>
 <tr><td>UPDATE_TRIGGER_REACTOR</td><td>Allow a user to update trigger reactors</td></tr>
 <tr><td>UPDATE_TRIGGER_VALIDATOR</td><td>Allow a user to update trigger validators</td></tr>
 <tr><td>UPDATE_USER</td><td>Allow a user to edit a user's record</td></tr>
 <tr><td>UPDATE_USER_BTYPE</td><td>UPDATE_USER_BTYPE</td></tr>
 <tr><td>UPDATE_VOLUME</td><td>Allow a user to edit volumes - needed for merging records. This is a duplicate of VOLUME_UPDATE; user must have both permissions at appropriate level to merge records.</td></tr>
 <tr><td>UPDATE_VOLUME_NOTE</td><td>UPDATE_VOLUME_NOTE</td></tr>
 <tr><td>UPDATE_VOLUME_PREFIX</td><td>Update prefix label definition.</td></tr>
 <tr><td>UPDATE_VOLUME_SUFFIX</td><td>Update suffix label definition.</td></tr>
 <tr><td>UPDATE_VR_FORMAT</td><td>UPDATE_VR_FORMAT</td></tr>
 <tr><td>UPDATE_WORKSTATION</td><td>Allows update of a workstation during workstation registration override.</td></tr>
 <tr><td>UPDATE_XML_TRANSFORM</td><td>UPDATE_XML_TRANSFORM</td></tr>
 <tr><td>URL_VERIFY</td><td>Allows a user to process and verify ULSs</td></tr>
 <tr><td>URL_VERIFY_UPDATE_SETTINGS</td><td>Allows a user to configure URL verification org unit settings</td></tr>
 <tr><td>VIEW_ACQ_FUNDING_SOURCE</td><td>VIEW_ACQ_FUNDING_SOURCE</td></tr>
 <tr><td>VIEW_ACQ_FUND_ALLOCATION_PERCENT</td><td>VIEW_ACQ_FUND_ALLOCATION_PERCENT</td></tr>
 <tr><td>VIEW_ADDRESS_ALERT</td><td>Allows a user to view address alerts</td></tr>
 <tr><td>VIEW_AUTHORITY_RECORD_NOTES</td><td>VIEW_AUTHORITY_RECORD_NOTES</td></tr>
 <tr><td>VIEW_BILLING_TYPE</td><td>Allow a user to view billing types</td></tr>
 <tr><td>VIEW_CIRCULATIONS</td><td>Allow a user to see what another user has checked out</td></tr>
 <tr><td>VIEW_CIRC_MATRIX_MATCHPOINT</td><td>VIEW_CIRC_MATRIX_MATCHPOINT</td></tr>
 <tr><td>VIEW_CLAIM</td><td>VIEW_CLAIM</td></tr>
 <tr><td>VIEW_CONTAINER</td><td>Allow a user to view another user's containers (buckets)</td></tr>
 <tr><td>VIEW_COPY_CHECKOUT_HISTORY</td><td>Allow a user to view which users have checked out a given copy</td></tr>
 <tr><td>VIEW_COPY_NOTES</td><td>Allow a user to view all notes attached to a copy</td></tr>
 <tr><td>VIEW_CREDIT_CARD_PROCESSING</td><td>View org unit settings related to credit card processing</td></tr>
 <tr><td>VIEW_FUND</td><td>Allow a user to view a fund</td></tr>
 <tr><td>VIEW_FUNDING_SOURCE</td><td>Allow a user to view a funding source</td></tr>
 <tr><td>VIEW_FUND_ALLOCATION</td><td>Allow a user to view a fund allocation</td></tr>
 <tr><td>VIEW_GROUP_PENALTY_THRESHOLD</td><td>VIEW_GROUP_PENALTY_THRESHOLD</td></tr>
 <tr><td>VIEW_HOLD</td><td>Allow a user to view another user's holds</td></tr>
 <tr><td>VIEW_HOLD_MATRIX_MATCHPOINT</td><td>VIEW_HOLD_MATRIX_MATCHPOINT</td></tr>
 <tr><td>VIEW_HOLD_NOTIFICATION</td><td>Allow a user to view notifications attached to a hold</td></tr>
 <tr><td>VIEW_HOLD_PERMIT</td><td>Allow a user to see if another user has permission to place a hold on a given copy</td></tr>
 <tr><td>VIEW_IMPORT_MATCH_SET</td><td>Allows a user to view vandelay match sets</td></tr>
 <tr><td>VIEW_INVOICE</td><td>VIEW_INVOICE</td></tr>
 <tr><td>VIEW_MERGE_PROFILE</td><td>VIEW_MERGE_PROFILE</td></tr>
 <tr><td>VIEW_ORG_SETTINGS</td><td>Allows a user to view all org settings at the specified level</td></tr>
 <tr><td>VIEW_PERMISSION</td><td>Allow a user to view user permissions within the user permissions editor</td></tr>
 <tr><td>VIEW_PERMIT_CHECKOUT</td><td>Allow a user to determine whether another user can check out an item</td></tr>
 <tr><td>VIEW_PERM_GROUPS</td><td>Allow a user to view other users' permission groups</td></tr>
 <tr><td>VIEW_PICKLIST</td><td>Allow a user to view another users picklist</td></tr>
 <tr><td>VIEW_PROVIDER</td><td>Allow a user to view a provider</td></tr>
 <tr><td>VIEW_PURCHASE_ORDER</td><td>Allows a user to view a purchase order</td></tr>
 <tr><td>VIEW_REPORT_OUTPUT</td><td>Allow a user to view report output</td></tr>
 <tr><td>VIEW_SEARCH_FILTER_GROUP</td><td>Allows staff to view search filter groups and entries</td></tr>
 <tr><td>VIEW_SERIAL_SUBSCRIPTION</td><td>VIEW_SERIAL_SUBSCRIPTION</td></tr>
 <tr><td>VIEW_STANDING_PENALTY</td><td>VIEW_STANDING_PENALTY</td></tr>
 <tr><td>VIEW_TITLE_NOTES</td><td>Allow a user to view all notes attached to a title</td></tr>
 <tr><td>VIEW_TRANSACTION</td><td>Allow a user may view another user's transactions</td></tr>
 <tr><td>VIEW_TRIGGER_EVENT</td><td>Allows a user to view circ- and hold-related action/trigger events</td></tr>
 <tr><td>VIEW_TRIGGER_EVENT_DEF</td><td>Allow a user to view trigger event definitions</td></tr>
 <tr><td>VIEW_USER</td><td>Allow a user to view another user's Patron Record</td></tr>
 <tr><td>VIEW_USER_FINES_SUMMARY</td><td>Allow a user to view bill details</td></tr>
 <tr><td>VIEW_USER_SETTING_TYPE</td><td>Allows viewing of configurable user setting types.</td></tr>
 <tr><td>VIEW_USER_TRANSACTIONS</td><td>Allow a user to see another user's grocery or circulation transactions in the Bills Interface; duplicate of VIEW_TRANSACTION</td></tr>
 <tr><td>VIEW_VOLUME_NOTES</td><td>Allow a user to view all notes attached to a volume</td></tr>
 <tr><td>VIEW_ZIP_DATA</td><td>Allow a user to query the ZIP code data method</td></tr>
 <tr><td>VOID_BILLING</td><td>Allow a user to void a bill</td></tr>
 <tr><td>VOLUME_HOLDS</td><td>Allow a user to place a volume level hold</td></tr>
 <tr><td>actor.org_unit.closed_date.create</td><td>Allow a user to create a new closed date for a location</td></tr>
 <tr><td>actor.org_unit.closed_date.delete</td><td>Allow a user to remove a closed date interval for a given location</td></tr>
 <tr><td>actor.org_unit.closed_date.update</td><td>Allow a user to update a closed date interval for a given location</td></tr>
 <tr><td>group_application.user</td><td>Allow a user to add/remove users to/from the "User" group</td></tr>
 <tr><td>group_application.user.patron</td><td>Allow a user to add/remove users to/from the "Patron" group</td></tr>
 <tr><td>group_application.user.sip_client</td><td>Allow a user to add/remove users to/from the "SIP-Client" group</td></tr>
 <tr><td>group_application.user.staff</td><td>Allow a user to add/remove users to/from the "Staff" group</td></tr>
 <tr><td>group_application.user.staff.acq</td><td>Allows a user to add/remove/edit users in the "ACQ" group</td></tr>
 <tr><td>group_application.user.staff.acq_admin</td><td>Allows a user to add/remove/edit users in the "Acquisitions Administrators" group</td></tr>
 <tr><td>group_application.user.staff.admin.global_admin</td><td>Allow a user to add/remove users to/from the "GlobalAdmin" group</td></tr>
 <tr><td>group_application.user.staff.admin.lib_manager</td><td>Allow a user to add/remove users to/from the "LibraryManager" group</td></tr>
 <tr><td>group_application.user.staff.admin.local_admin</td><td>Allow a user to add/remove users to/from the "LocalAdmin" group</td></tr>
 <tr><td>group_application.user.staff.cat</td><td>Allow a user to add/remove users to/from the "Cataloger" group</td></tr>
 <tr><td>group_application.user.staff.cat.cat1</td><td>Allow a user to add/remove users to/from the "Cat1" group</td></tr>
 <tr><td>group_application.user.staff.circ</td><td>Allow a user to add/remove users to/from the "Circulator" group</td></tr>
 <tr><td>group_application.user.staff.supercat</td><td>Allow a user to add/remove users to/from the "Supercat" group</td></tr>
 <tr><td>group_application.user.vendor</td><td>Allow a user to add/remove users to/from the "Vendor" group</td></tr>
 <tr><td>money.collections_tracker.create</td><td>Allow a user to put someone into collections</td></tr>
 <tr><td>money.collections_tracker.delete</td><td>Allow a user to remove someone from collections</td></tr>
 <tr><td>user_request.create</td><td>user_request.create</td></tr>
 <tr><td>user_request.delete</td><td>user_request.delete</td></tr>
 <tr><td>user_request.update</td><td>user_request.update</td></tr>
 <tr><td>user_request.view</td><td>user_request.view</td></tr>
</table>
<br>