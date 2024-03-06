ARG version
FROM almalinux:${version}
#FROM almalinux:${version:-8} //If ther user forget to use the version it will take default version as 8
# ARG variable before FROM will not work after FROM
RUN echo "This is Version number: ${version}"