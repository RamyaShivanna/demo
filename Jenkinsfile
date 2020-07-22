node {
stage ('build')
{
parallel(
"1st":
{
build ( job: 'job1)
},
"2nd":
{
build (job: 'job2')
}
)
}
}
