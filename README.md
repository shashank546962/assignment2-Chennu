# assignment2-Chennu
# chennu venkata shashankar
##### KFC is my favourite place to buy food

I have found of very well known park near by **KFC**. I love to be there twice a day. I will be enjoying there with kids over there, The **climate** there is vibrant and have picturesque view and have grocery Store to buy things we need.

---

#### Direction to the Novotel Hotel  from Airport

**BEGUMPET Airport** is the nearest airport to Hotel where I can get all the food stuff that I love

1. Take the left turn from the x cross road
2. Take the exit number 10 to NH22 Highway
3. Follow the path after 60 kilometers you will find NH36
4. Continue upto 200 kilometers on NH36
5. When you get into the Hyderabad city follow the instrcutions to get on Highway 
6. Take the right turn and follow on road upto 20 kilometers to the national highway
7. Take the exit to cross road on the exit 20 on the left you can find novotel hotel

#### Food Advice for Novice at novotel hotel
* Chicken Dum biriyani
* Mutton Biriyani
* Burge Masala
* Chicken Soup
  * Paya soup
  * Haleem 
* Fish mandi

---

#### Sports Suggestions

The below table that I m going to show is the sports activities to recomend newbies 

| sports | Location | Equipment cost |
|:------|:--------:|---------------:|
|Badminton| CA Stadium| $50 |
|Kho Kho| Ramnagar| $30|
|Tennis|Attapur|$60|
|Rugby|Jhon Grounds|$90|

---

### quotes

---

> If you can dream it, you can do it.<br>
                                     *walt disney*

> Be a Life Long Learner.<br>
                         *Robert*

---

## Data Structures

> we will get to know the Data Structure sparse table code.

[Description for sparse table](https://cp-algorithms.com/data_structures/sparse-table.html)

Below is the code

---

int st[MAXN][K + 1];
for (int i = 0; i < N; i++)
    st[i][0] = f(array[i]);

for (int j = 1; j <= K; j++)
    for (int i = 0; i + (1 << j) <= N; i++)
        st[i][j] = f(st[i][j-1], st[i + (1 << (j - 1))][j - 1]);
        ong long st[MAXN][K + 1];

for (int i = 0; i < N; i++)
    st[i][0] = array[i];

for (int j = 1; j <= K; j++)
    for (int i = 0; i + (1 << j) <= N; i++)
        st[i][j] = st[i][j-1] + st[i + (1 << (j - 1))][j - 1];
        long long sum = 0;
for (int j = K; j >= 0; j--) {
    if ((1 << j) <= R - L + 1) {
        sum += st[L][j];
        L += 1 << j;
    }
}
int log[MAXN+1];
log[1] = 0;
for (int i = 2; i <= MAXN; i++)
    log[i] = log[i/2] + 1;
    int st[MAXN][K + 1];

for (int i = 0; i < N; i++)
    st[i][0] = array[i];

for (int j = 1; j <= K; j++)
    for (int i = 0; i + (1 << j) <= N; i++)
        st[i][j] = min(st[i][j-1], st[i + (1 << (j - 1))][j - 1]);
        int j = log[R - L + 1];
int minimum = min(st[L][j], st[R - (1 << j) + 1][j]);

   }
};



---

[Code Source](https://cp-algorithms.com/data_structures/sparse-table.html)



![Shashankar](https://github.com/shashank546962/assignment2-Chennu/blob/main/123.jpeg)

Image **[Shashankar!](https://github.com/shashank546962/assignment2-Chennu/blob/main/123.jpeg)**