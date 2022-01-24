# Old images

## dotnet-library-test
Docker Hub: https://hub.docker.com/repository/docker/hullcritical/dotnet-library-test

### dotnet-library-test:release-glibc-v6

Built from  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-6/Dockerfile.glibc

Used by  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-6/Dockerfile.glibc.runner#L10

### dotnet-library-test:release-musl

Built from  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-5/Dockerfile.musl

Used by  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-5/Dockerfile.musl.runner#L10

### dotnet-library-test:release-glibc

Built from  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-5/Dockerfile.glibc

Used by  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-5/Dockerfile.glibc.runner#L10

## aspnetcore
Docker Hub: https://hub.docker.com/repository/docker/hullcritical/aspnetcore

### aspnetcore:5

Built from  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/aspnetcore5/Dockerfile.aspnet5

Used by  
https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/aspnetcore5/Dockerfile.runner#L9

# New images

There should be two repos

## dotnet-library-test
Tag:
* release-glibc-v6  
    Built from https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-6/Dockerfile.glibc
* release-musl-v5  
    Built from https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-5/Dockerfile.musl
* release-glibc-v5  
    Built from https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/dotnet-lib-5/Dockerfile.glibc

## aspnetcore
Tag:
* debug-glibc-v5  
    Built from  
    https://github.com/asvrada/mystikos/blob/dotnet_lib_6/tests/aspnetcore5/Dockerfile.aspnet5
