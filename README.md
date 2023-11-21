pipeline
{
agent any
stages
{
stage{
step('validate')
{
echo('i am validating')
}
}
stage{
steps('compile')
{
echo('i am compiling')
}
}
stage{
steps('instal')
{
echo('i am installing')
}
}
}
