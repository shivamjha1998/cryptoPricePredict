# Crypto Currency Price Prediction
## version 0.10.000
For this first version we wanted to set up a base point for our model, and then start building it further.
The graph below compares the real prices (in black) against our model predicted prices (in green).![Actual Price vs Predicted Price](https://lh3.googleusercontent.com/ZbVegzSI5PyMJKWG3lefQ2kXgXNjB47fCbtNxOC_cK0uvVs4ibpXKbD-TiFI7jqXIurSO-kY6-pAtdNKwt-xnvLDAiFUYx79fzBaejhLh79syHPIhzOu2Mp_iYcOkg8Y90bXjCj6koAW65FZCVhZ9gDXJXT_FYkNu4X-49JDAOpTujvlOQGoomrJjZmH7QDAQQmbuwJ-Cxmn1QvEP0KUBq2TuFLac4jyBw8b4kLUgnwo-_coll_Pcmwt0qKR7cUaunzpgi9hNGfz-qqyfMsBz0rf4doGDZ65gxi_Sw_4i-FvQC24TRlWwEYPdIT5xxt4_agCMtFNjH3OFLxTaMZPAjP9nHV4E44OLRPBDQSvtOaNjbGAzMXS-4JKvQLRqPmPtodgqEgTSu_14H7jDVRHqQf9IL_EMi29JnICo6uATIeY61LGLvR60F4UEGgujI3-1-1skZFWdXOFjTZpd0ceX1a8HQA_DEfumxCmpooCyv5O6tPIILzxeHc4Jb4Ie0JqU3aerBUw587yZCJt7q0WcEdjUHXRvy7gfW0nd3wDDwrSkMH7K0vUd0YVYlK3c33TCFJJMA-Y5GcaoZvLNMVwMlsBMim9XshFFrVe6qZdFcc6Hcq9cSF64ZZdIA1Lhc0RJlcAw3U26NdO96pJWrzZnVxeYXu1wUzRkUsD5vigmJt8NIjSUPnNZlI_sh17P4ppKNJ7OAztALTarARriKxF7CA=w401-h278-no?authuser=0)


For the model we made use of simple LSTM layer with 3 dropout layer and a Dense layer, also we divided the data in 80 20 split.

