# servicenow
if priority will be P1,it  will populate on opening the ticket.
function onLoad() {
   //Type appropriate comment here, and begin script below
   var pri = g_form.getValue('priority');
   if(pri=='1'){
	alert("This is a P1 incident!");
   }
   
}
