very powerful command that check if all branches are the same as the repo 

example


$ git branch -vv
  Test_Branch                     3611884 [origin/Test_Branch] cleanup
* dev                             5ec25bc [origin/dev] now devfile is part of dev
  main                            3611884 [origin/main] cleanup
  mistake1                        71a1848 [origin/mistake1] everything back to order
  test_git_push_n                 5ec25bc now devfile is part of dev
  test_git_stash_push             ad36bbd [origin/test_git_stash_push] deleted to delete
  understanding_head_concept      0234501 [origin/understanding_head_concept] just tested and adde 2-THE-HEAD.md
  understanding_head_concept_test 0234501 [origin/understanding_head_concept_test] just tested and adde 2-THE-HEAD. md
  update-readme                   4b1c22a [origin/update-readme] Initial commit
  
   main                            3611884 [origin/main] cleanup
   this for example means that main is uptodate (same commit in local same as cloud)
   
   test_git_push_n                 5ec25bc now devfile is part of dev
   this means that test_git_push_n only have a commit localy


