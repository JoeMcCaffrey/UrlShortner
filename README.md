# UrlShortner
 
// Work done on edlab by Joseph McCaffrey

/**
 * The `shortener` function returns an object containing functions
 * of the following form:
 *
 *   {
 *     shorten,
 *     expand,
 *     digits,
 *     path,
 *     nextid
 *   }
 *
 * See the documentation for each function below.
 *
 * @example
 * var shortly = shortener(alphabet, protocol, ids);
 * shortly.shorten('http://www.google.com') => 'http://short.ly/bef'
 * shortly.expand('http://short.ly/bef') => 'http://www.google.com'
 *
 * @param alphabet the alphabet that will be used in the shortened URL
 * @param protocol the protocol and domain used in the shortened URL
 * @param ids a starting ID that is used for shortening the URL
 * @returns an object of functions
 */

