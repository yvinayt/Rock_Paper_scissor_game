#include<iostream>
#include<cstdlib>
#include<vector>
#include<time.h>

using namespace std;

int main()
{
    vector<string> item_list = {"Rock", "Paper", "Scissor"};
    string user_choice;

    cout<<"Enter your choice in Rock, Paper, Scissor....";
    cin>>user_choice;

    srand(time(NULL));
    int rand_index = rand()%3;

    string comp_choice;
    comp_choice = item_list[rand_index];

    if (user_choice == comp_choice)
        cout<<"Match Tie";

    else if (user_choice == "Rock")
        if (comp_choice == "Paper")
            cout<<"Paper covers Rock, Computer wins";
        else
            cout<<"Rock smashes Scissor, You won";

    else if (user_choice == "Paper")
        if (comp_choice == "Scissor")
            cout<<"Scissor cuts Paper, Computer wins";
        else
            cout<<"Paper covers Rock, You won";

    else if (user_choice == "Scissor")
        if (comp_choice == "Rock")
            cout<<"Rock smashes Scissor, Computer won";
        else
            cout<<"Scissor cuts Paper, You won";

    return 0;
}
