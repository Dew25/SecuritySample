SecuritySample.

Compilation:
javac securitysample/SecuritySample.java securitysample/SampleLoginModule.java securitysample/SamplePrincipal.java
Run:
java -Djava.security.auth.login.config==sample_jass.config securitysample.SecuritySample

login: testLogin
Password: testPassword