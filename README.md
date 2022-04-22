# Supported-
 Global Const $AuthNumberOfAuthMethodsSupported = 2 Global Const $AuthMethodNoAuthenticationRequired = 0x00 Global Const $AuthMethodUsernamePassword = 0x02  Local $ProxyHost = "your Socks5 server hostname"; Local $ProxyPort = "your Socks5 server port"; Local $Username = "User name" Local $Password = "Password"  TCPStartup() Opt("TCPTimeout", 5000)  ; 1. Connect to Proxy
