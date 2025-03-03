
[ req ]
default_bits = 2048
default_keyfile = rui.key
distinguished_name = req_distinguished_name
encrypt_key = no
prompt = no
string_mask = nombstr
req_extensions = v3_req
[ v3_req ]
basicConstraints = CA:FALSE
keyUsage = digitalSignature, keyEncipherment, dataEncipherment
extendedKeyUsage = serverAuth, clientAuth
subjectAltName = DNS:esxi002, IP:192.168.182.130, DNS:esxi002.cyrus-consultants.co.uk

[ req_distinguished_name ]
countryName = GB
stateOrProvinceName = East Riding of Yorkshire
localityName = York
0.organizationName = Cyrus HQ
organizationalUnitName = Cyrus Copmputer Consultants Ltd
commonName = esxi002.cyrus-consultants.co.uk
