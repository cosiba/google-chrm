touch ~/.gitcookies
chmod 0600 ~/.gitcookies

git config --global http.cookiefile ~/.gitcookies

tr , \\t <<\__END__ >>~/.gitcookies
chromium.googlesource.com,FALSE,/,TRUE,2147483647,o,git-cosorhaner.gmail.com=1/j-dVMsLqtDECYuu6V1x9jyev-A1Aj1byz_Vc_R4HcOxHE1QTNAd8h0jZIpbwZMst
chromium-review.googlesource.com,FALSE,/,TRUE,2147483647,o,git-cosorhaner.gmail.com=1/j-dVMsLqtDECYuu6V1x9jyev-A1Aj1byz_Vc_R4HcOxHE1QTNAd8h0jZIpbwZMst
__END__
