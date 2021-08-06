No need to be changed anymore
==============================

Cipher Suites (23 suites) FF 27.0.1
    Cipher Suite: TLS_ECDHE_ECDSA_WITH_AES_128_GCM_SHA256 (0xc02b)
    Cipher Suite: TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256 (0xc02f)
    Cipher Suite: TLS_ECDHE_ECDSA_WITH_AES_256_CBC_SHA (0xc00a)
    Cipher Suite: TLS_ECDHE_ECDSA_WITH_AES_128_CBC_SHA (0xc009)
    Cipher Suite: TLS_ECDHE_RSA_WITH_AES_128_CBC_SHA (0xc013)
    Cipher Suite: TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA (0xc014)
    Cipher Suite: TLS_ECDHE_RSA_WITH_3DES_EDE_CBC_SHA (0xc012)
    Cipher Suite: TLS_ECDHE_ECDSA_WITH_RC4_128_SHA (0xc007)
    Cipher Suite: TLS_ECDHE_RSA_WITH_RC4_128_SHA (0xc011)
    Cipher Suite: TLS_DHE_RSA_WITH_AES_128_CBC_SHA (0x0033)
    Cipher Suite: TLS_DHE_DSS_WITH_AES_128_CBC_SHA (0x0032)
    Cipher Suite: TLS_DHE_RSA_WITH_CAMELLIA_128_CBC_SHA (0x0045)
    Cipher Suite: TLS_DHE_RSA_WITH_AES_256_CBC_SHA (0x0039)
    Cipher Suite: TLS_DHE_DSS_WITH_AES_256_CBC_SHA (0x0038)
    Cipher Suite: TLS_DHE_RSA_WITH_CAMELLIA_256_CBC_SHA (0x0088)
    Cipher Suite: TLS_DHE_RSA_WITH_3DES_EDE_CBC_SHA (0x0016)
    Cipher Suite: TLS_RSA_WITH_AES_128_CBC_SHA (0x002f)
    Cipher Suite: TLS_RSA_WITH_CAMELLIA_128_CBC_SHA (0x0041)
    Cipher Suite: TLS_RSA_WITH_AES_256_CBC_SHA (0x0035)
    Cipher Suite: TLS_RSA_WITH_CAMELLIA_256_CBC_SHA (0x0084)
    Cipher Suite: TLS_RSA_WITH_3DES_EDE_CBC_SHA (0x000a)
    Cipher Suite: TLS_RSA_WITH_RC4_128_SHA (0x0005)
    Cipher Suite: TLS_RSA_WITH_RC4_128_MD5 (0x0004)

	
Compared to FF 41.0.2

Cipher Suites (8 suites)
    Cipher Suite: TLS_ECDHE_ECDSA_WITH_AES_128_GCM_SHA256 (0xc02b)
    Cipher Suite: TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256 (0xc02f)
    Cipher Suite: TLS_ECDHE_ECDSA_WITH_AES_256_CBC_SHA (0xc00a)
    Cipher Suite: TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA (0xc014)
    Cipher Suite: TLS_RSA_WITH_AES_128_CBC_SHA (0x002f)
    Cipher Suite: TLS_RSA_WITH_AES_256_CBC_SHA (0x0035)
	
	
Total:

    user_pref("security.ssl3.rsa_null_sha", false);
    user_pref("security.ssl3.rsa_null_md5", false);
    user_pref("security.ssl3.ecdhe_rsa_null_sha", false);
    user_pref("security.ssl3.ecdhe_ecdsa_null_sha", false);
    user_pref("security.ssl3.ecdh_rsa_null_sha", false);
    user_pref("security.ssl3.ecdh_ecdsa_null_sha", false);
    user_pref("security.ssl3.rsa_seed_sha", false);
    user_pref("security.ssl3.rsa_rc4_40_md5", false);
    user_pref("security.ssl3.rsa_rc2_40_md5", false);
    user_pref("security.ssl3.rsa_1024_rc4_56_sha", false);
    user_pref("security.ssl3.rsa_camellia_128_sha", false);
    user_pref("security.ssl3.ecdhe_rsa_aes_128_sha", false);
    user_pref("security.ssl3.ecdhe_ecdsa_aes_128_sha", false);
    user_pref("security.ssl3.ecdh_rsa_aes_128_sha", false);
    user_pref("security.ssl3.ecdh_ecdsa_aes_128_sha", false);
    user_pref("security.ssl3.dhe_rsa_camellia_128_sha", false);
    user_pref("security.ssl3.dhe_rsa_aes_128_sha", false);
    user_pref("security.ssl3.ecdh_ecdsa_rc4_128_sha", false);
    user_pref("security.ssl3.ecdh_rsa_rc4_128_sha", false);
    user_pref("security.ssl3.ecdhe_ecdsa_rc4_128_sha", false);
    user_pref("security.ssl3.ecdhe_rsa_rc4_128_sha", false);
    user_pref("security.ssl3.rsa_rc4_128_md5", false);
    user_pref("security.ssl3.rsa_rc4_128_sha", false);
    user_pref("security.ssl3.dhe_dss_des_ede3_sha", false);
    user_pref("security.ssl3.dhe_rsa_des_ede3_sha", false);
    user_pref("security.ssl3.ecdh_ecdsa_des_ede3_sha", false);
    user_pref("security.ssl3.ecdh_rsa_des_ede3_sha", false);
    user_pref("security.ssl3.ecdhe_ecdsa_des_ede3_sha", false);
    user_pref("security.ssl3.ecdhe_rsa_des_ede3_sha", false);
    user_pref("security.ssl3.rsa_des_ede3_sha", false);
    user_pref("security.ssl3.rsa_fips_des_ede3_sha", false);
    user_pref("security.ssl3.ecdh_rsa_aes_256_sha", false);
    user_pref("security.ssl3.ecdh_ecdsa_aes_256_sha", false);
    user_pref("security.ssl3.rsa_camellia_256_sha", false);
    user_pref("security.ssl3.ecdhe_rsa_aes_256_sha", true);
    user_pref("security.ssl3.ecdhe_ecdsa_aes_256_sha", true);
    user_pref("security.ssl3.ecdhe_ecdsa_aes_128_gcm_sha256", true);
    user_pref("security.ssl3.ecdhe_rsa_aes_128_gcm_sha256", true);
    user_pref("security.ssl3.ecdhe_ecdsa_chacha20_poly1305_sha256", true);
    user_pref("security.ssl3.ecdhe_rsa_chacha20_poly1305_sha256", true);
    user_pref("security.ssl3.dhe_rsa_camellia_256_sha", false);
    user_pref("security.ssl3.dhe_rsa_aes_256_sha", false);
    user_pref("security.ssl3.rsa_aes_256_sha", true);
    user_pref("security.ssl3.rsa_aes_128_sha", true);
	

Resource:
* https://www.owasp.org/index.php/Testing_for_Weak_SSL/TLS_Ciphers,_Insufficient_Transport_Layer_Protection_(OTG-CRYPST-001)
