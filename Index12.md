<html>
    <head>
        <title>
            Registration Form by Ninna Alessandra Santiago
        </title>
        <meta name="student" content="Ninna Alessandra Santiago">
        <meta name="description" content="Forms">
        <meta name="keywords" content="HTML">
        <style>
            .myDiv {
              border: 3px outset rgb(48, 42, 85); 
              text-align: center;
            }
            </style>
    </head>
    <body>
        <div class="myDiv" style="font-family: 'Courier New'; font-size: 12pt; text-align: center;"><b>
            <p>
                <a href="Index.html" target="_blank">Homepage</a>
            </p>
            <p>
                <a href="Index1.html" target="_blank">Activity 1</a>
                <a href="Index2.html" target="_blank">Activity 2</a>
                <a href="Index3.html" target="_blank">Activity 3</a>
            </p>
            <p>
                <a href="Index4.html" target="_blank">Activity 4.1</a>
                <a href="Index5.html" target="_blank">Activity 4.2</a>
            </p>
            <p>
                <a href="Index6.html" target="_blank">Activity 5.1</a>
                <a href="Index7.html" target="_blank">Activity 5.2</a>
                <a href="Index8.html" target="_blank">Activity 5.3</a>
                <a href="Index9.html" target="_blank">Activity 5.4</a>
                <a href="Index10.html" target="_blank">Activity 5.5</a>
                <a href="Index11.html" target="_blank">Activity 5.6</a>
            </p>
            <p>
                Activity 6
            </p>
            </b>
            </div>
        <p><img src="University_of_Baguio_textlogo.png" height="100px" width="300px"></p>
        <p><h2 style="text-align: center; font-family:'Courier New'; color: brown;">
            Student Profile
        </h2></p><br><br>
        <form action="/action_page.php" style="font-family: helvetica; font-size: 15px; color: black">
            <label for="snumber">Student number &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:</label>
            <input type="text" id="snumber" size="30" maxlength="8" required><br><br>
            <label for="sname">Student Name &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="sname" size="20" placeholder="Surname" required>
            &nbsp;
            <input type="text" id="sname" size="30" placeholder="Given name" required>
            &nbsp;
            <input type="text" id="sname" size="20" placeholder="Middle name" required>
            <br><br>
            <label for="course">Course/Program &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <select id="course" name="course" required>
                <option value="Course"> - Course - </option>
                <option value="Associate in Computer Technology">Associate in Computer Technology</option>
                <option value="BS Computer Science">BS Computer Science</option>
                <option value="BS Information Technology">BS Information Technology</option>
                <option value="BS Computer Engineering">BS Computer Engineering</option>
                <option value="Cisco Certified Entry Level (CCENT)">Cisco Certified Entry Level (CCENT)</option>
                <option value="Cisco Certified Network Associate (CCNA)">Cisco Certified Network Associate (CCNA)</option></select>
                <br>
                <br>
            <label for="mnumber">Mobile No. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="mnumber" name="mnumber" maxlength="11" required>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="email">E-mail address &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="email" name="email" maxlength="8" required>
            <label for="email">@s.ubaguio.edu</label><br><br>
            <label for="raddress">Residential Address &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="raddress" name="raddress" size="50">
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="paddress">Permanent Address &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="paddress" name="paddress" size="50" required>
            <br><br>
            <label for="pregion">(Permanent) Region &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <select id="pregion" name="pregion" required>
                <option value="Region I – Ilocos Region">Region I – Ilocos Region</option>
                <option value="Region II – Cagayan Valley">Region II – Cagayan Valley</option>
                <option value="Region III – Central Luzon">Region III – Central Luzon</option>
                <option value="Region IV‑A – CALABARZON">Region IV‑A – CALABARZON</option>
                <option value="MIMAROPA Region">MIMAROPA Region</option>
                <option value="Region V – Bicol Region">Region V – Bicol Region</option>
                <option value="Region VI – Western Visayas">Region VI – Western Visayas</option>
                <option value="Region VII – Central Visayas">Region VII – Central Visayas</option>
                <option value="Region VIII – Eastern Visayas">Region VIII – Eastern Visayas</option>
                <option value="Region IX – Zamboanga Peninsula">Region IX – Zamboanga Peninsula</option>
                <option value="Region X – Northern Mindanao">Region X – Northern Mindanao</option>
                <option value="Region XI – Davao Region">Region XI – Davao Region</option>
                <option value="Region XII – SOCCSKSARGEN">Region XII – SOCCSKSARGEN</option>
                <option value="Region XIII – Caraga">Region XIII – Caraga</option>
                <option value="NCR – National Capital Region">NCR – National Capital Region</option>
                <option value="CAR – Cordillera Administrative Region">CAR – Cordillera Administrative Region</option>
                <option value="ARMM – Autonomous Region in Muslim Mindanao">ARMM – Autonomous Region in Muslim Mindanao</option>
            </select>
            <br><br>
            <label for="pprovince">(Permanent) Province &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <select id="pprovince" name="pprovince" required>
                <option value="Abra">Abra</option>
                <option value="Agusan Del Norte">Agusan Del Norte</option>
                <option value="Agusan Del Sur">Agusan Del Sur</option>
                <option value="Aklan">Aklan</option>
                <option value="Albay">Albay</option>
                <option value="Antique">Antique</option>
                <option value="Apayao">Apayao</option>
                <option value="Aurora">Aurora</option>
                <option value="Basilan">Basilan</option>
                <option value="Bataan">Bataan</option>
                <option value="Batanes">Batanes</option>
                <option value="Batangas">Batangas</option>
                <option value="Benguet">Benguet</option>
                <option value="Biliran">Biliran</option>
                <option value="Bohol">Bukidnon</option>
                <option value="Bulacan">Bulacan</option>
                <option value="Cagayan">Cagayan</option>
                <option value="Camarines Norte">Camarines Norte</option>
                <option value="Camarines Sur">Camarines Sur</option>
                <option value="Camiguin">Camiguin</option>
                <option value="Capiz">Capiz</option>
                <option value="Catanduanes">Catanduanes</option>
                <option value="Cavite">Cavite</option>
                <option value="Cebu">Cebu</option>
                <option value="Compostella Valley">Compostella Valley</option>
                <option value="Cotabato">Cotabato</option>
                <option value="Davao Del Norte">Davao Del Norte</option>
                <option value="Davao Del Sur">Davao Del Sur</option>
                <option value="Davao Occidental">Davao Occidental</option>
                <option value="Davao Oriental">Davao Oriental</option>
                <option value="Dinagat Islands">Dinagat Islands</option>
                <option value="Eastern Samar">Eastern Samar</option>
                <option value="Guimaras">Guimaras</option>
                <option value="Ifugao">Ifugao</option>
                <option value="Ilocos Norte">Ilocos Norte</option>
                <option value="Ilocos Sur">Ilocos Sur</option>
                <option value="Iloilo">Iloilo</option>
                <option value="Isabela">Isabela</option>
                <option value="Kalinga">Kalinga</option>
                <option value="La Union">La Union</option>
                <option value="Laguna">Laguna</option>
                <option value="Lanao Del Norte">Lanao Del Norte</option>
                <option value="Lanao Del Sur">Lanao Del Sur</option>
                <option value="Leyte">Leyte</option>
                <option value="Maguindanao">Maguindanao</option>
                <option value="Marindique">Marindique</option>
                <option value="Masbate">Masbate</option>
                <option value="Misamis Occidental">Misamis Occidental</option>
                <option value="Misamis Oriental">Misamis Oriental</option>
                <option value="Mountain Province">Mountain Province</option>
                <option value="Negros Occidental">Negros Occidental</option>
                <option value="Negros Oriental">Negros Oriental</option>
                <option value="Northern Samar">Northern Samar</option>
                <option value="Nueva Ecija">Nueva Ecija</option>
                <option value="Nueva Vizcaya">Nueva Vizcaya</option>
                <option value="Occidental Mindoro">Occidental Mindoro</option>
                <option value="Oriental Mindoro">Oriental Mindoro</option>
                <option value="Palawan">Palawan</option>
                <option value="Pampanga">Pampanga</option>
                <option value="Pangasinan">Pangasinan</option>
                <option value="Quezon">Quezon</option>
                <option value="Quirino">Quirino</option>
                <option value="Rizal">Rizal</option>
                <option value="Romblon">Romblon</option>
                <option value="Samar">Samar</option>
                <option value="Sarangani">Sarangani</option>
                <option value="Siquijor">Siquijor</option>
                <option value="Sorsogon">Sorsogon</option>
                <option value="South Cotabato">South Cotabato</option>
                <option value="Southern Leyte">Southern Leyte</option>
                <option value="Sultan Kudarat">Sultan Kudarat</option>
                <option value="Sulu">Sulu</option>
                <option value="Surigao Del Norte">Surigao Del Norte</option>
                <option value="Surigao Del Sur">Surigao Del Sur</option>
                <option value="Tarlac">Tarlac</option>
                <option value="Tawi-Tawi">Tawi-Tawi</option>
                <option value="Zambales">Zambales</option>
                <option value="Zamboanga Del Norte">Zamboanga Del Norte</option>
                <option value="Zamboanga Del Sur">Zamboanga Del Sur</option>
                <option value="Zamboanga Sibugay">Zamboanga Sibugay</option>
            </select>
            <br><br>
            <label for="pmunicipality">(Permanent) Municipality &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="pmunicipality" name="pmunicipality" required>
            <br><br>
            <label for="ptel">Permanent Tel. No. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="tel" id="phone" name="phone"
            placeholder="123-45-678"
            pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
            maxlength="9">
            <br><br>
            <label for="birthday">Date of Birth &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <select id="birthday" name="birthday" required>
                <option value="Month">Month</option>
                <option value="January">January</option>
                <option value="February">February</option>
                <option value="March">March</option>
                <option value="April">April</option>
                <option value="May">May</option>
                <option value="June">June</option>
                <option value="July">July</option>
                <option value="August">August</option>
                <option value="September">September</option>
                <option value="October">October</option>
                <option value="November">November</option>
                <option value="December">December</option>
            </select>
            &nbsp;
            <select id="birthday" name="birthday" required>
                <option value="day">Day</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
                <option value="11">11</option>
                <option value="12">12</option>
                <option value="13">13</option>
                <option value="14">14</option>
                <option value="15">15</option>
                <option value="16">16</option>
                <option value="17">17</option>
                <option value="18">18</option>
                <option value="19">19</option>
                <option value="20">20</option>
                <option value="21">21</option>
                <option value="22">22</option>
                <option value="23">23</option>
                <option value="24">24</option>
                <option value="25">25</option>
                <option value="26">26</option>
                <option value="27">27</option>
                <option value="28">28</option>
                <option value="29">29</option>
                <option value="30">30</option>
                <option value="31">31</option>
            </select>
            &nbsp;
            <input type="text" id="birthday" name="birthday" size="8" maxlength="4" placeholder="Year" required>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="birthplace">Place of Birth &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="birthplace" name="birthplace" required>
            <br><br>
            <label for="gender">Gender &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="radio" id="gender" name="gender" value="Male" required>
            <label for="gender">Male</label>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="religion">Religion &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="religion" name="religion" required><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <input type="radio" id="gender" name="gender" value="Female" required>
            <label for="gender">Female</label>
            <br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <input type="radio" id="gender" name="gender" value="Other(please specify)">
            <label for="gender">Other(please specify):</label>
            <input type="text" id="gender" name="gender">
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="status">Civil Status &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <select id="status" name="status" required>
                <option value="single">Single</option>
                <option value="married">Married</option>
                <option value="divorced">Divorced</option>
                <option value="annulled">Annulled</option>
                <option value="widowed">Widowed</option>
            </select>
            <br><br>
            <label for="nationality">Nationality &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</label>
            <input type="text" id="nationality" name="nationality" required>
            <br><br>
            <input type="submit" value="Submit">
        </form>
    </body>
</html>
