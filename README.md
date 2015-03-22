# CreativeZone
This is creative platform where you can get all the new stuff related to bootstrap and asp.net.



<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head><title>

</title>
<meta charset="utf-8" /><meta name="viewport" content="width=device-width, initial-scale=1" /><link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css" />
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <style type="text/css">
        .btn {
        height:50px;
        background-color:rgba(168, 71, 71 , 0.5);
        }
        corner {
        box-shadow: 10px 10px 5px #888888;
        border-radius:15%;
        }
    </style>
</head>
<body>
    <form method="post" action="Net_Banking.aspx" id="form1">
<div class="aspNetHidden">
<input type="hidden" name="__VIEWSTATE" id="__VIEWSTATE" value="Td0df/tIXgbUKiHiXqLNhRMT3xqyneGetlJrs73x9eIOG5wZJXOVH5fZzBIAj0asSLm+AYnnI4xgR+4MNludeYav/KT/Qq6dS9OTLmWEj3Ub87q15+EAL+wjZE/eTSBOyq+DMtWevCTzjBmoLGE9B5JyxvI9TBMTErzr1AW+loNSZ/pIRbJ/T6N82OiFW7NGE6mGQvqa2D6O1FoP6+ukXeODsYWFr6FiLZDj/bCxCJ78JqiWuyDCzSx6YGngMRomo2OUkWJOWIPdPduNPdAfqTWlZljb+lfDUdjKaqTPPwbw8DHwHVGbAo/rI/wQP4meg1n23KtDPtunQvOFu/Vfrw==" />
</div>

        <br /><br /><br /><br /><br /><br />
    <div class="container">
        <div class="row corner" style="background-color:#d4f18c">
            <br /><br /><br /> 
        </div>
        <div class="row">
        <div class="col-md-2">
            <a href="Net_Banking.aspx"<input type="submit" name="ctl00$btn_net_banking" value="Net Banking" id="btn_net_banking" class="btn btn-primary btn-lg btn-block" />Net Banking</a>
            <a href="Debit_Card.aspx"<input type="submit" name="ctl00$btn_debit_card" value="Debit Card" id="btn_debit_card" class="btn btn-primary btn-lg btn-block" />Debit Card</a>
            <a href="Credit_Card.aspx"<input type="submit" name="ctl00$btn_credid_card" value="Credit Card" id="btn_credid_card" class="btn btn-primary btn-lg btn-block" />Credit Card</a>
            <a href="COD.aspx"<input type="submit" name="ctl00$btn_cod" value="COD" id="btn_cod" class="btn btn-primary btn-lg btn-block" />C.O.D</a>
            <a href="Vallet.aspx"<input type="submit" name="ctl00$btn_vallet" value="COD" id="btn_vallet" class="btn btn-primary btn-lg btn-block" />Vallet</a>
            <a href="Coupon.aspx"<input type="submit" name="ctl00$btn_cuppon" value="COD" id="btn_cuppon" class="btn btn-primary btn-lg btn-block" />Coupon</a>
        </div>
        <div class="col-md-8">
             <div class="row">
                <div class="col-md-2">

                    <input id="sbi" type="radio" name="ctl00$hh" value="sbi" /><label for="sbi">SBI</label>
                </div>
                <div class="col-md-2">
                    <input id="icici" type="radio" name="ctl00$hh" value="icici" /><label for="icici">ICICI</label>
                </div>
                <div class="col-md-2">
                    <input id="hdfc" type="radio" name="ctl00$hh" value="hdfc" /><label for="hdfc">HDFC</label>
                </div>
                <div class="col-md-2">
                    <input id="axis" type="radio" name="ctl00$hh" value="axis" /><label for="axis">AXIS</label>
                </div>
                <div class="col-md-2">
                    <input id="pnb" type="radio" name="ctl00$hh" value="pnb" /><label for="pnb">PNB</label>
                </div>
                <div class="col-md-2">
                   <input id="citi" type="radio" name="ctl00$hh" value="citi" /><label for="citi">CITI</label>
                </div>
            </div>
             
    <div class="row">
        <div class="col-lg-2"></div>
        <div class="col-lg-8" style="text-align:center ; background-color:azure">
            <br />
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    <strong>Name :</strong>
                </div>
                 <div class="col-lg-6" style="text-align:left">
                    <input name="ctl00$ContentPlaceHolder1$nbname" type="text" id="ContentPlaceHolder1_nbname" class="form-control" />
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    <strong>Account No. :</strong>
                </div>
                 <div class="col-lg-6" style="text-align:left">
                    <input name="ctl00$ContentPlaceHolder1$nbaccount" type="text" id="ContentPlaceHolder1_nbaccount" class="form-control" />
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    <strong>Password :</strong>
                </div>
                 <div class="col-lg-6" style="text-align:left">
                    <input name="ctl00$ContentPlaceHolder1$nbpassword" type="password" id="ContentPlaceHolder1_nbpassword" class="form-control" />
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    <strong>Confirm Password :</strong>
                </div>
                 <div class="col-lg-6" style="text-align:left">
                    <input name="ctl00$ContentPlaceHolder1$nbcnfpassword" type="text" id="ContentPlaceHolder1_nbcnfpassword" class="form-control" />
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    <strong>OTP :</strong>
                </div>
                 <div class="col-lg-6" style="text-align:left">
                    <input name="ctl00$ContentPlaceHolder1$nbotp" type="text" id="ContentPlaceHolder1_nbotp" class="form-control" />
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    <strong>Mobile No. :</strong>
                </div>
                 <div class="col-lg-6" style="text-align:left">
                    <input name="ctl00$ContentPlaceHolder1$mobile" type="text" id="ContentPlaceHolder1_mobile" class="form-control" />
                </div>
            </div>
            <br />
            <div class="row">
                <div class="col-lg-6" style="text-align:right">
                    
                </div>
                 <div class="col-lg-6" style="text-align:left">
                     <input type="submit" name="ctl00$ContentPlaceHolder1$nb_submit" value="Submit" id="ContentPlaceHolder1_nb_submit" class="btn btn-default" />
                    <input type="submit" name="ctl00$ContentPlaceHolder1$nb_clear" value="Clear" id="ContentPlaceHolder1_nb_clear" class="btn btn-default pull-right" />
                </div>
            </div>

        </div>
        <div class="col-lg-2"></div>
    </div>


        </div>
        <div class="col-md-2"></div>
       </div>
        <div class="row" style="background-color:#d4f18c">
            <br /><br /><br /> 
        </div>
    </div>
    
<div class="aspNetHidden">

	<input type="hidden" name="__VIEWSTATEGENERATOR" id="__VIEWSTATEGENERATOR" value="13AFE333" />
	<input type="hidden" name="__EVENTVALIDATION" id="__EVENTVALIDATION" value="UHI8sO2ELJeTcpFwUK0m13dl/lbZq3UOpOUWXKhWhLU4m8t0FX2jaKhfGValFsK7V8LnOrRbvcALJ6ZwqAW8N7AASf9pWHdp+t08m0bQ3k7k/ibL95cFjqaLqkzdMnaLulrPJn2IMIW6IsvMLzzrewHdkW4ImAeqSl7UhetFpRNsb/mlFxSsPlK6Z1ubBq34q3Yh/70red+dGXCjQgV34rxPbonwb5caBOemq5eoNaA8NkaeCgQqT7ymAm+l5TYctHTSVaQW7o9sTmtBNygMlf2XQIfev5Sc+qRsl+TwCuByyvNo9gDRhEQrswRrlA8Yb2VZS6chLCnuwwEFnF3gGhgX79smaSO/JfNDDV/qARZJ80oeHpzTQDAqNUbxczwVlf6vKZuSOl3ZloonPYqUhs/WK4B8qwNCDLjXDCkP7GSZejsBNAiFiWddzNj7Yhd+iqXWwkQ444qPkOTrTVzk9rviAj0iCbXfUkqH66AMXZEGRXQPhJxk1CGTdYEZOMWJ/eFesCQXkamKaWnvSfGbtQ==" />
</div></form>

<!-- Visual Studio Browser Link -->
<script type="application/json" id="__browserLink_initializationData">
    {"appName":"Chrome","requestId":"097103d450e74615936aecf7bcc1094a"}
</script>
<script type="text/javascript" src="http://localhost:7857/2bc910760dfb46968a20c5520f039d66/browserLink" async="async"></script>
<!-- End Browser Link -->

</body>
</html>
