// ================= WORD SEARCH GAME =================
class WordSearch : public Game
{
public:
    WordSearch(int d) : Game(d) {}

    string getGameName()
    {
        return "Word Search";
    }

    int play()
    {
        score = 0;

        string guess;

        cout << "\n*************************\n";
        cout << " WORD SEARCH GAME\n";
        cout << "*************************\n";

        char grid[5][5] =
        {
            {'P','S','D','E','Q'},
            {'G','T','S','A','U'},
            {'T','A','G','M','E'},
            {'G','C','M','A','U'},
            {'P','K','A','E','E'}
        };

        for(int i=0;i<5;i++)
        {
            for(int j=0;j<5;j++)
            {
                cout << grid[i][j] << " ";
            }
            cout << endl;
        }

        string words[3] =
        {
            "STACK","QUEUE","GAME"
        };

        cout << "\nFind hidden words!\n";

        for(int i=0;i<3;i++)
        {
            cout << "Enter word: ";
            cin >> guess;

            if(guess == words[i] ||
               guess == "stack" ||
               guess == "queue" ||
               guess == "game")
            {
                cout << "Correct!\n";
                score++;
            }
            else
            {
                cout << "Wrong!\n";
            }
        }

        cout << "\nFinal Score: "
             << score << "/3\n";

        score = (score * 10) / 3;

        return score;
    }
};
