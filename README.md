# sipp
Two Scenarios are discussed

A. Registration of sipp

Do the following sipp

1.Install sipp in linux 

2.Create CSV file like below

"SEQUENTIAL
nitin087495390386876558217943;phone.plivo.com;[authentication username=nitin087495390386876558217943 password=12345];nitin6915892551468831;"

3. For doing Registration run below command from cli messages are dumped in  -message_file Filename

Registering user1
"sipp -sf client.xml -inf reg_dataclient1.csv -m 1 -l 1 -trace_msg  -trace_err phone.plivo.com -log_file reg.log -log_overwrite true -message_file msgfile1 -p 6000"

Registering user2
"sipp -sf client.xml -inf reg_dataclient2.csv -m 1 -l 1 -trace_msg  -trace_err phone.plivo.com -log_file reg.log -log_overwrite true -message_file msgfile -p 7000" 
