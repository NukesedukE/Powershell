#reboot Windows if no user is logged in

$fooErrorActionPreference = "Continue"
$fooUserStatus = quser
if(!$fooUserStatus){
    Restart-Computer -Force ;exit
    }
else{
    exit 0
    }
