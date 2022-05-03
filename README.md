| 시퀀스 다이어그램  |  |  |
|------------|--|--|
| 다이어그램 명 |  | genreSVCImpl |
| 작성일  |  | 2021-11-02 |
| 다이어그램 설명 |  |  |

| Caller 클래스명 | Caller 메소드 | Callee 클래스명 | Callee 메소드 | 담당자 | 작성일 |
|-------------|------------|-------------|------------|-----|-----|
| genreBIZ | genreInOutBvo delete(genreInOutBvo) | genreDAO | int delete(genreInOutDvo) | SCORE | 2021-11-02 |
| genreSVCImpl | genreInOutSvo delete(genreInOutSvo) | genreBIZ | genreInOutBvo delete(genreInOutBvo) | SCORE | 2021-11-02 |
| genreBIZ | genreInOutBvo delete(genreInOutBvo) | genreDAO | int delete(genreInOutDvo) | SCORE | 2021-11-02 |
