<h1>Course Registration form</h1>
<form action="https://leetcode.com/jyothishwar91642/">
    <fieldset>
        <table>
            <legend>Personal Details</legend>
        <tr><td><label>First Name</label></td><td><input type="text" name="FN" placeholder="Ex:Rohit"><br></td>
        </tr>
        <tr><td><label>SurName</label></td><td><input type="text" name="SN" placeholder="Ex:Reddy"></td></tr>
        <tr><td><label> MobileNumber</label></td><td><input type="tel" name="mob" placeholder="Ex:7019589699"></td></tr>
        <tr><td><label>Email</label></td><td><input type="email" name="Email" placeholder="Ex:Rohit@gmail.com"></td></tr>
        <tr><td><label>Password</label></td><td><input type="password" name="password" placeholder="Ex:min 5 characters"></td></tr>
        <tr><td><label>ConfirmPassword</label></td><td><input type="password" name="cpassword" placeholder="Ex:min 5 characters"></td></tr>
        <tr><td><label>DOB</label></td><td><input type="date" name="date"></td></tr>
        <tr><td><label>Gender</label></td><td><input type="radio" name="Gender" value="M">Male 
            <input type="radio" name="Gender" value="F">Female 
            <input type="radio" name="Gender" value="C">Custom </td></tr>
        <tr><td><label>Select Country</label></td><td><select name="Country">
            <option value="INDIA">INDIA</option>
            <option value="USA">USA</option>
            <option value="CHINA">CHINA</option>
        </select></td></tr>
        <tr><td><label>Upload Picture</label></td><td><input type="file" name="pic"></td></tr>
        <tr><td><input type="reset"></td></tr>
        </table>
    </fieldset>

    <fieldset>
        <legend>Course Details</legend>
        <table>
           <tr><td> <label>Select course</label></td><td><select name="course">
            <option value="Java">JAVA</option>
            <option value="Python">PYTHON</option>
            <option value="DSA">DSA</option>
        </select><br></td></tr>
        <tr><td><label>Delivery mode</label></td><td><input type="checkbox" name="mode1" value="ON">ONLINE
            <input type="checkbox" name="mode2" value="OFF">OFFLINE <br>
<label>Comments</label><br><textarea cols="40" rows="5"></textarea></td></tr>
        </table>

    </fieldset>

    <input type="submit">
</form>
