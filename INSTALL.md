# Instalação

mkdir -p /usr/bin /usr/lib/smallpkg /etc /etc/smallpkg /var/lib/smallpkg
cp smallpkg/smallpkg /usr/bin/
cp smallpkg/repo /usr/lib/smallpkg/
cp smallpkg-conf/smallpkg.conf /etc/
cp smallpkg-conf/repo.conf /etc/smallpkg/
chmod +x /usr/bin/smallpkg /usr/lib/smallpkg/repo
