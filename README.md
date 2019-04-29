# hello-world
//I've seen them from the hub
//JUST SUCCESSFULLY THREW AWAY MY CHANGES
//just to get settled
//that's it.
//Use your earth mouth not your mars mouth.
//add in isaacs code to test
//add code

#include <sys/types.h>
#include <unistd.h>
#include <stdio.h>
#include <stdlib.h>
// what is the difference between exit() and return()??


int main () {
  pid_t pid = 0;
  pid = fork();
  if(pid < 0) {
    printf("could not create process\n");
    exit(1);
  } else if(pid == 0) { 
    \\sleep(1);
    \\see what effect it has
    printf("Hello from the child process\n");
  } else if(pid > 0) {
  printf("Hello from the parent process.\n");
  }
  printf("This code will be executed by both the child and the parent\n");
}
