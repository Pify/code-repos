# code-repos
fungsi yang akan berguna di masa depan


fun getRandomString(): String {
    val allowedChars = ('A'..'Z') + ('0'..'9')
    return (1..5).map { allowedChars.random() }.joinToString("")
}


fun getAscendingData(name: String, limit: Int) {
    var array: ArrayList<String> = ArrayList()
    for( i in 1..limit) {
        array.add("$name$i")
    }
    return print(array)
}
