node {
stage ('build')
{
parallel(
"1st":
{
build ( job: 'job1')
},
"2nd":
{
git clone 'https://github.com/RamyaShivanna/demo.git'
}
)
}
}
