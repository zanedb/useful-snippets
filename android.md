## Useful Android Snippets

#### Toast Message

You may also use `getString(R.string.yourstring)` instead of `""`, and be sure to replace `CurrentActivity` with whatever Activity this code runs in, or alternatively a context.

    Toast.makeText(CurrentActivity.this, "", Toast.LENGTH_SHORT).show();
