# collectntingstest

/* Start of Phone Number Field */

.phoneFormFieldBlock {
    padding: 12px 10px;
    /*padding: 12px 30px;*/ /* [Yo] From for Testing (copy) */
     label {
        font-family: "Segoe UI", Arial, sans-serif;
        font-size: 16px;
        font-weight: 600;
        /* display: block;
        margin-top: 3px; */
    } 
     label::after {
        width: 22px;
        display: inline-block;
        line-height: 22px;
        text-align: center;
        color: rgb(195, 52, 0);
        content: "*";
    }
         input {
            position: relative;
            margin-top: 16px; /*19px*/
            padding: 6px 8px;
            background: rgb(250, 249, 248);
            border: 1px solid rgb(225, 223, 221);
            border-radius: 2px;
            display: block;
            width: 100%;
            height: 32px; /*33px*/
            box-sizing: border-box;
            font-size: 14px;
            line-height: 20px;
    }
}

/* End of Phone Number Field */
