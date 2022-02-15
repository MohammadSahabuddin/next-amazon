ctrl+shipt+P=> (open the setting)=> type json => open === open setting(JSON)

add====>
"javascript.format.enable": false,
"prettier.singleQuote":true ,
"editor.formatOnSave": true,

Lessons:::

1.  Basics of Code Editors "18/11/21" "0:00:00"
2.  Initial commit Cr.N.Ap. "18/11/21" "0:10:00"
3.  Create-Next-App-Layout "18/11/21" "0:17:50"
4.  Add-Styles-To-Layout "18/11/21" "0:27:00"
    prob:{
    Can't resolve '@emotion/react'=>
    sln=>> check and add then restart the site
    "@emotion/react": "^11.5.0",
    "@emotion/styled": "^11.3.0",
    "@material-ui/core": "^4.12.3",
    "@mui/material": "^5.0.6",
    }
5.  Fix-SSR-MaterialUI-Styles "18/11/21" "0:32:40"
6.  List-Products "19/11/21" "0:41:55"
7.  Add-Header-Links "19/11/21" "0:53:15"
8.  Route-Product-Page "19/11/21" "0:58:25"
9.  Create-Product Details-Page "19/11/21" "1:06:40"
10. Add-MaterialUI-Theme "19/11/21" "1:22:32"
11. Create-Application-Context "20/11/21" "1:29:25"
    //Api (backend)
12. Connect-To-MongoDB "20/11/21" "1:42:53"
13. Create-Products-API "20/11/21" "1:56:42"
14. Fetch Products-From-API "21/11/21" "2:07:42"
    {if have error "products is undefined" then see from 2:11:00 }
15. Implement-Add-to-cart "21/11/21" "2:19:42"
16. Create-Cart-Screen "22/11/21" "2:33:42"
    [when clicking add to cart its took me to "/cart" page becaus I implement
    {
    const router = useRouter();
    and also in dispatch
    router.push('/cart');
    }]

17. 1.  Use-Dynamic-Import-In-Cart-Screen "22/11/21" "2:49:00"
        note: [in "2:49:00"
        consoling the problem {" Expected server HTML to contain a matching <span> in <a>.
        at span"}

                         because in the serverSide rendering there is not any cookie but in the client site there is badge thats why we get this warning in the badge component
                         For solving the issue we will render the server in the client side not in server.
                         check the link 'nextjs.org/docs/advanced-features/dynamic-import']

    2.  Use-Dynamic-Import-In-Cart-Screen-Fix "22/11/21" "2:53:00"

18. Update-Remove-Items-In-Cart "22/11/21" "2:58:28"
19. Create-Login-Screen "23/11/21" "3:06:27"
20. Create Sample-Users "23/11/21" "3:16:27"
21. Build-Login-API "23/11/21" "3:22:15"
    NOTE: [ in ".env" file need to add
    JWT_SECRET = somethingsecret ]
22. Build-Login-API "24/11/21" "3:34:47"
23. Create-Register-Page "26/11/21" "3:48:47"
24. Login-and-Register-form-validation "27/11/21" "3:55:22"
    NOTE:[install=>"npm install react-hook-form"]
    "npm install notistack" 24. Login-and-Register-form-validation "27/11/21" "4:07:03"
25. Create-Shipping-Page "27/11/21" "4:12:14"
    {
    hare have a problem. the data isn't save the values in cookies
    }
26. Create-Payment-Page "28/11/21" "4:25:20"
27. Create-Place-Order-Page "28/11/21" "4:40:20"
28. Implement-Place-Order-Action "29/11/21" "4:53:20"
29. Create-Order-Details "30/11/21" "5:11:30"
    need to see => 5:00:00
30. Pay-Order-By-PayPal "1/12/21" "5:34:30"
31. Display-Orders-History "2/12/21" "6:00:54"
32. Update-User-Profile "2/12/21" "6:17:06"
33. Create-Admin-Dashboard "17/12/21" "fo-11"
34. Manage Orders "24/12/21" "fo-12 V-1"
35. Deliver Order for Admin "24/12/21" "fo-12 V-2"
36. Manage Products "01/01/22"
    1. List Product "01/01/22" "fo-13 V-1"
    2. Create Product Edit Page "02/01/22" "fo-13 V-2"
    3. Update Product "03/01/22" "fo-13 v-3"
    4. Upload Product Image "14/01/22" "fo-13 v-4" [cloudinary.com/users/register/free]
    5. Create And Delete Products
37. Manage Users
    1. List Users
    2. Edit Users
38. Deploy no Vercel

I have completed "0:03:40" v "0:05:35"
