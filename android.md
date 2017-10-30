## Useful Android Snippets

#### Toast Message

You may also use `getString(R.string.yourstring)` instead of `""`, and be sure to replace `CurrentActivity` with whatever Activity this code runs in, or alternatively a context.

    Toast.makeText(CurrentActivity.this, "", Toast.LENGTH_SHORT).show();

#### Intents

A one line version is below. Be sure to change `NewActivity` to the activity you wish to open.

    startActivity(new Intent(this, NewActivity.class));
    
Using multiple lines, again following the same rules as above:

    Intent intent = new Intent(this, NewActivity.class);
    startActivity(intent);
