We have used struct and slice to store the data.
No data is being used




                            __________ Get All   --------  getMovies  ---------  /movies     ---------  GET  ------------- |
                            |                                                                                               |
                            |                                                                                               |
                            |                                                                                               |
                            __________ GET BY ID --------- getMovie    --------- /movies/id  ---------  GET -------------- |
                            |                                                                                               |
                            |                                                                                               |
                            |                                                                                               |
        movies server-----|---------- CREATE    --------- createMovie ----------- /movie  ------------  POST ------------- |-----------POSTMAN
                            |                                                                                               |
                            |                                                                                               |
                            |                                                                                               |
                            |__________ UPDATE    --------- updateMoview --------- /movies/id ---------   PUT ------------- |
                            |                                                                                               |
                            |                                                                                               |
                            |                                                                                               |
                            ----------- DELETE   ---------- deleteMovie ---------- /movies/id ---------- DELETE -----------|


To run the code:
make run



