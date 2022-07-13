# first
<!doctpe html>
<html>
    <head>
        <meta charset="utf-8">
        <title>e25</title>
    </head>
    <body>
        <form dir="rtl">
            <fieldset style="color: crimson; font-family:B Nazanin">
                <legend align="center" style="color: brown">ثبت نام</legend>
                <p style="color: red; font-size: 12px">نکته1: پر کردن فیلد های * الزامیست.</p>
                <p style="color: red; font-size: 12px">نکته2: از صحت اطلاعات وارد شده اطمینان حاصل نمائید.</p>
                <label>نام *:</label>
                <input type="text" name="firstname" placeholder="نام خود را وارد کنید" required><br>
                <label>نام خانوادگی *:</label>
                <input type="text" name="lastname" placeholder="نام خانوادگی خود را وارد کنید:" required><br>
                <label>کدملی*:</label>
                <input type="number" name="casenamber" placeholder="کد ملی" size="10" required><br>
                <label>تلفن همراه*:</label>
                <input type="number" name="phonenumber" placeholder="تلفن همراه" required><br>
                <label>کدپستی:</label>
                <input type="number" name="postcode" placeholder="کدپستی" required><br>
                <label>email*:</label>
                <input type="email" name="email" placeholder="email" required>
                <hr>
                <label>بارگذاری عکس پرسنلی* :</label>
                <input type="file" name="photo" placeholder="عکس پرسنلی" required><br>
                <hr>
                <label>کشور*:</label>
                    <select>
                        <option>ایران</option>
                        <option>عراق</option>
                        <option>ترکیه</option>
                        <option>آلمان</option>
                        <option>تایلند</option>
                        <option>آمریکا</option>
                    </select>
                <br>
                <label>دین*:</label>
                    <select>
                        <option>اسلام</option>
                        <option>کلیمی</option>
                        <option>مسیحی</option>
                        <option>زرتشتی</option>
                        <option>اقلیت های مذهبی</option>
                    </select>
                <hr>
                <label>سهمیه ایثارگری*:</label>
                    <span>بالای 50 درصد</span>
                    <input type="radio" name="sahmiyeh">
                    <span>بین 25 تا 50 درصد</span>
                    <input type="radio" name="sahmiyeh">
                    <span>زیر 25 درصد</span>
                    <input type="radio" name="sahmiyeh">
                <hr>
            <input type="submit" value="ثبت اطلاعات">
                
                
                
                
            </fieldset>
        </form>
    </body>
</html>
