# Volley Error Android

```
@Override
public void onErrorResponse(VolleyError error) {

    if (error instanceof TimeoutError || error instanceof NoConnectionError) {
        Toast.makeText(context,
                context.getString(R.string.error_network_timeout),
                Toast.LENGTH_LONG).show();
    } else if (error instanceof AuthFailureError) {
        //TODO
    } else if (error instanceof ServerError) {
       //TODO
    } else if (error instanceof NetworkError) {
      //TODO
    } else if (error instanceof ParseError) {
       //TODO
    }
}
```
