- Signup in pusher.com

- Open browser in index.html

- Post URL:

curl -H "Content-Type: application/json" -d "hello world" \
"http://api.pusherapp.com/apps/31423/channels/test_channel/events?"\
"name=my_event&"\
"body_md5=5eb63bbbe01eeed093cb22bb8f5acdc3&"\
"auth_version=1.0&"\
"auth_key=894b79a83ea135a14918&"\
"auth_timestamp=1352544247&"\
"auth_signature=0b7c088575e2bb696dfb760531dba5cbebcec46f2f7ef75432ca332b25e5eb6b&"
