```
1896  mkdir 20-Helm-Custom-Charts
 1897  ls
 1898  cd 20-Helm-Custom-Charts/
 1899  ls
 1900  mkdir v1
 1901  ls
 1902  d v1/
 1903  cd v1/
 1904  s
 1905  ls
 1906  helm create my-tiny-webapp
 1907  ls
 1908  tree my-tiny-webapp
 1909  cd my-tiny-webapp/
 1910  ls
 1911  cat templates/service.yaml
 1912  ls
 1913  vim values.yaml
 1914  ls
 1915  cat Chart.yaml
 1916  ls
 1917  cd ..
 1918  ls
 1919  helm install my-web my-tiny-webapp --dry-run
 1920  helm install my-web my-tiny-webapp
 1921  helm list
 1922  kubectl get deploy,pod,svc
 1923  ls
 1924  cd ..
 1925  ls
 1926  cp -rf v1 v2
 1927  ls
 1928  cd v2/
 1929  ls
 1930  cd my-tiny-webapp/
 1931  ls
 1932  vim Chart.yaml
 1933  ls
 1934  vim values.yaml
 1935  ls
 1936  cd ..
 1937  ls
 1938  helm install my-web my-tiny-webapp --dry-run
 1939  helm install my-web-v2 my-tiny-webapp
 1940  helm list
 1941  helm upgrade my-web my-tiny-webapp
 1942  helm list
 1943  kubectl get deploy
 1944  kubectl get po
 1945  kubectl get svc
 1946  curl 172.23.0.3:30717
 1947  curl 172.23.0.3:30906
 1948  ls
 1949  cd ..
 1950  ls
 1951  cp -rf v2 v3
 1952  ls
 1953  cd v3/
 1954  ls
 1955  cd my-tiny-webapp/
 1956  ls
 1957  vim values.yaml
 1958  ls
 1959  cd ..
 1960  ls
 1961  cd ..
 1962  helm list
 1963  kubectl get svc
 1964  curl 172.23.0.3:30717
 1965  ls
 1966  cd v3/
 1967  ls
 1968  vim my-tiny-webapp/Chart.yaml
 1969  ls
 1970  helm upgrade my-web my-tiny-webapp
 1971  helm list
 1972  curl 172.23.0.3:30717
 1973  kubectl get po
 1974  curl 172.23.0.3:30717
 1975  helm list
 1976  helm history my-web
 1977  helm rollback my-web
 1978  helm history my-web
 1979  kubectl get po
 1980  curl 172.23.0.3:30717
 1981  helm rollback my-web
 1982  kubectl get po
 1983  curl 172.23.0.3:30717
 1984  helm history my-web
 1985  helm rollback my-web 1
 1986  helm history my-web
 1987  kubectl get po
 1988  kubectl get svc
```
