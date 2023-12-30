# CodeIgniter 4 Snippets for VSCode

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-codeigniter4-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-codeigniter4-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-codeigniter4-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-codeigniter4-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-codeigniter4-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-codeigniter4-snippets/blob/main/LICENSE)

This extension for Visual Studio Code adds snippets for CodeIgniter 4 Framework. With this extension, you can easily write CodeIgniter 4 Framework code.

![demo](https://raw.githubusercontent.com/ManuelGil/vscode-codeigniter4-snippets/main/docs/images/demo.gif)

## Requirements

- CodeIgniter 4.3.0 or later
- VSCode 1.46.0 or later

## Usage

### Spark

| Snippet | Purpose |
| --- | --- |
| ci:class:config | class config |
| ci:class:controller | class controller |
| ci:class:entity | class entity |
| ci:class:filter | class filter |
| ci:class:migration | class migration |
| ci:class:model | class model |
| ci:class:seeder | class seeder |
| ci:class:validation | class validation |

### Functions

| Snippet | Purpose |
| --- | --- |
| ci:app_timezone | app_timezone |
| ci:cache | cache |
| ci:clean_path | clean_path |
| ci:command | command |
| ci:config | config |
| ci:cookie | cookie |
| ci:cookies | cookies |
| ci:csrf_token | csrf_token |
| ci:csrf_header | csrf_header |
| ci:csrf_hash | csrf_hash |
| ci:csrf_field | csrf_field |
| ci:csrf_meta | csrf_meta |
| ci:csp_style_nonce | csp_style_nonce |
| ci:csp_script_nonce | csp_script_nonce |
| ci:db_connect | db_connect |
| ci:env | env |
| ci:esc | esc |
| ci:force_https | force_https |
| ci:function_usable | function_usable |
| ci:helper | helper |
| ci:is_cli | is_cli |
| ci:is_really_writable | is_really_writable |
| ci:is_windows | is_windows |
| ci:lang | lang |
| ci:log_message | log_message |
| ci:model | model |
| ci:old | old |
| ci:redirect | redirect |
| ci:_solidus | _solidus |
| ci:remove_invisible_characters | remove_invisible_characters |
| ci:request | request |
| ci:response | response |
| ci:route_to | route_to |
| ci:session | session |
| ci:service | service |
| ci:single_service | single_service |
| ci:slash_item | slash_item |
| ci:stringify_attributes | stringify_attributes |
| ci:timer | timer |
| ci:view | view |
| ci:view_cell | view_cell |
| ci:class_basename | class_basename |
| ci:class_uses_recursive | class_uses_recursive |
| ci:trait_uses_recursive | trait_uses_recursive |

### Constants

| Snippet | Purpose |
| --- | --- |
| ci:CI_VERSION | CI_VERSION |
| ci:ENVIRONMENT | ENVIRONMENT |
| ci:APPPATH | APPPATH |
| ci:ROOTPATH | ROOTPATH |
| ci:SYSTEMPATH | SYSTEMPATH |
| ci:FCPATH | FCPATH |
| ci:WRITEPATH | WRITEPATH |
| ci:SECOND | SECOND |
| ci:MINUTE | MINUTE |
| ci:HOUR | HOUR |
| ci:DAY | DAY |
| ci:WEEK | WEEK |
| ci:MONTH | MONTH |
| ci:YEAR | YEAR |
| ci:DECADE | DECADE |

### Query Builder

| Snippet | Purpose |
| --- | --- |
| ci:builder:db | $builder->db |
| ci:testMode | testMode |
| ci:getTable | getTable |
| ci:getBinds | getBinds |
| ci:ignore | ignore |
| ci:select | select |
| ci:selectMax | selectMax |
| ci:selectMin | selectMin |
| ci:selectAvg | selectAvg |
| ci:selectSum | selectSum |
| ci:selectCount | selectCount |
| ci:selectSubquery | selectSubquery |
| ci:distinct | distinct |
| ci:from | from |
| ci:fromSubquery | fromSubquery |
| ci:join | join |
| ci:where | where |
| ci:orWhere | orWhere |
| ci:whereIn | whereIn |
| ci:orWhereIn | orWhereIn |
| ci:whereNotIn | whereNotIn |
| ci:orWhereNotIn | orWhereNotIn |
| ci:havingIn | havingIn |
| ci:orHavingIn | orHavingIn |
| ci:havingNotIn | havingNotIn |
| ci:orHavingNotIn | orHavingNotIn |
| ci:like | like |
| ci:notLike | notLike |
| ci:orLike | orLike |
| ci:orNotLike | orNotLike |
| ci:havingLike | havingLike |
| ci:notHavingLike | notHavingLike |
| ci:orHavingLike | orHavingLike |
| ci:orNotHavingLike | orNotHavingLike |
| ci:union | union |
| ci:unionAll | unionAll |
| ci:groupStart | groupStart |
| ci:orGroupStart | orGroupStart |
| ci:notGroupStart | notGroupStart |
| ci:orNotGroupStart | orNotGroupStart |
| ci:groupEnd | groupEnd |
| ci:havingGroupStart | havingGroupStart |
| ci:orHavingGroupStart | orHavingGroupStart |
| ci:notHavingGroupStart | notHavingGroupStart |
| ci:orNotHavingGroupStart | orNotHavingGroupStart |
| ci:havingGroupEnd | havingGroupEnd |
| ci:groupBy | groupBy |
| ci:having | having |
| ci:orHaving | orHaving |
| ci:orderBy | orderBy |
| ci:limit | limit |
| ci:offset | offset |
| ci:set | set |
| ci:getSetData | getSetData |
| ci:getCompiledSelect | getCompiledSelect |
| ci:get | get |
| ci:countAll | countAll |
| ci:countAllResults | countAllResults |
| ci:getCompiledQBWhere | getCompiledQBWhere |
| ci:getWhere | getWhere |
| ci:setData | setData |
| ci:getCompiledUpsert | getCompiledUpsert |
| ci:upsert | upsert |
| ci:upsertBatch | upsertBatch |
| ci:updateFields | updateFields |
| ci:onConstraint | onConstraint |
| ci:setQueryAsData | setQueryAsData |
| ci:insertBatch | insertBatch |
| ci:setInsertBatch | setInsertBatch |
| ci:getCompiledInsert | getCompiledInsert |
| ci:insert | insert |
| ci:replace | replace |
| ci:getCompiledUpdate | getCompiledUpdate |
| ci:update | update |
| ci:updateBatch | updateBatch |
| ci:setUpdateBatch | setUpdateBatch |
| ci:emptyTable | emptyTable |
| ci:truncate | truncate |
| ci:getCompiledDelete | getCompiledDelete |
| ci:delete | delete |
| ci:deleteBatch | deleteBatch |
| ci:increment | increment |
| ci:decrement | decrement |
| ci:resetQuery | resetQuery |

### Cookie

| Snippet | Purpose |
| --- | --- |
| ci:cookie:setDefaults | Cookie::setDefaults |
| ci:cookie:fromHeaderString | Cookie::fromHeaderString |
| ci:cookie:getId | $cookie->getId |
| ci:cookie:getPrefix | $cookie->getPrefix |
| ci:cookie:getName | $cookie->getName |
| ci:cookie:getPrefixedName | $cookie->getPrefixedName |
| ci:cookie:getValue | $cookie->getValue |
| ci:cookie:getExpiresTimestamp | $cookie->getExpiresTimestamp |
| ci:cookie:getExpiresString | $cookie->getExpiresString |
| ci:cookie:isExpired | $cookie->isExpired |
| ci:cookie:getMaxAge | $cookie->getMaxAge |
| ci:cookie:getPath | $cookie->getPath |
| ci:cookie:getDomain | $cookie->getDomain |
| ci:cookie:isSecure | $cookie->isSecure |
| ci:cookie:isHTTPOnly | $cookie->isHTTPOnly |
| ci:cookie:getSameSite | $cookie->getSameSite |
| ci:cookie:isRaw | $cookie->isRaw |
| ci:cookie:getOptions | $cookie->getOptions |
| ci:cookie:withPrefix | $cookie->withPrefix |
| ci:cookie:withName | $cookie->withName |
| ci:cookie:withValue | $cookie->withValue |
| ci:cookie:withExpires | $cookie->withExpires |
| ci:cookie:withExpired | $cookie->withExpired |
| ci:cookie:withPath | $cookie->withPath |
| ci:cookie:withDomain | $cookie->withDomain |
| ci:cookie:withSecure | $cookie->withSecure |
| ci:cookie:withHTTPOnly | $cookie->withHTTPOnly |
| ci:cookie:withSameSite | $cookie->withSameSite |
| ci:cookie:withRaw | $cookie->withRaw |
| ci:cookie:offsetExists | $cookie->offsetExists |
| ci:cookie:offsetGet | $cookie->offsetGet |
| ci:cookie:offsetSet | $cookie->offsetSet |
| ci:cookie:offsetUnset | $cookie->offsetUnset |
| ci:cookie:toHeaderString | $cookie->toHeaderString |
| ci:cookie:toArray | $cookie->toArray |
| ci:cookie:set_cookie | set_cookie |
| ci:cookie:get_cookie | get_cookie |
| ci:cookie:delete_cookie | delete_cookie |
| ci:cookie:has_cookie | has_cookie |

### Database

| Snippet | Purpose |
| --- | --- |
| ci:db | $db |
| ci:db:reconnect | $db->reconnect |
| ci:db:close | $db->close |
| ci:db:query | $db->query |
| ci:db:simpleQuery | $db->simpleQuery |
| ci:db:prefixTable | $db->prefixTable |
| ci:db:affectedRows | $db->affectedRows |
| ci:db:escape | $db->escape |
| ci:db:escapeString | $db->escapeString |
| ci:db:escapeLikeString | $db->escapeLikeString |
| ci:db:setPrefix | $db->setPrefix |
| ci:db:getPrefix | $db->getPrefix |
| ci:db:getPlatform | $db->getPlatform |
| ci:db:setAliasedTables | $db->setAliasedTables |
| ci:db:addTableAlias | $db->addTableAlias |
| ci:db:execute | $db->execute |
| ci:db:transOff | $db->transOff |
| ci:db:transStrict | $db->transStrict |
| ci:db:transStart | $db->transStart |
| ci:db:transException | $db->transException |
| ci:db:transComplete | $db->transComplete |
| ci:db:transStatus | $db->transStatus |
| ci:db:transBegin | $db->transBegin |
| ci:db:transCommit | $db->transCommit |
| ci:db:transRollback | $db->transRollback |
| ci:db:table | $db->table |
| ci:db:newQuery | $db->newQuery |
| ci:db:prepare | $db->prepare |
| ci:db:getLastQuery | $db->getLastQuery |
| ci:db:showLastQuery | $db->showLastQuery |
| ci:db:getConnectStart | $db->getConnectStart |
| ci:db:getConnectDuration | $db->getConnectDuration |
| ci:db:protectIdentifiers | $db->protectIdentifiers |
| ci:db:escapeIdentifiers | $db->escapeIdentifiers |
| ci:db:listTables | $db->listTables |
| ci:db:tableExists | $db->tableExists |
| ci:db:getFieldNames | $db->getFieldNames |
| ci:db:fieldExists | $db->fieldExists |
| ci:db:getFieldData | $db->getFieldData |
| ci:db:getIndexData | $db->getIndexData |
| ci:db:getForeignKeyData | $db->getForeignKeyData |
| ci:db:disableForeignKeyChecks | $db->disableForeignKeyChecks |
| ci:db:enableForeignKeyChecks | $db->enableForeignKeyChecks |
| ci:db:pretend | $db->pretend |
| ci:db:resetDataCache | $db->resetDataCache |
| ci:db:isWriteType | $db->isWriteType |
| ci:db:error | $db->error |
| ci:db:insertID | $db->insertID |

### Email

| Snippet | Purpose |
| --- | --- |
| ci:email:initialize | $email->initialize |
| ci:email:clear | $email->clear |
| ci:email:setFrom | $email->setFrom |
| ci:email:setReplyTo | $email->setReplyTo |
| ci:email:setTo | $email->setTo |
| ci:email:setCC | $email->setCC |
| ci:email:setBCC | $email->setBCC |
| ci:email:setSubject | $email->setSubject |
| ci:email:setMessage | $email->setMessage |
| ci:email:attach | $email->attach |
| ci:email:setAttachmentCID | $email->setAttachmentCID |
| ci:email:setHeader | $email->setHeader |
| ci:email:setAltMessage | $email->setAltMessage |
| ci:email:setMailType | $email->setMailType |
| ci:email:setWordWrap | $email->setWordWrap |
| ci:email:setProtocol | $email->setProtocol |
| ci:email:setPriority | $email->setPriority |
| ci:email:setNewline | $email->setNewline |
| ci:email:setCRLF | $email->setCRLF |
| ci:email:validateEmail | $email->validateEmail |
| ci:email:isValidEmail | $email->isValidEmail |
| ci:email:cleanEmail | $email->cleanEmail |
| ci:email:wordWrap | $email->wordWrap |
| ci:email:send | $email->send |
| ci:email:batchBCCSend | $email->batchBCCSend |
| ci:email:printDebugger | $email->printDebugger |
| ci:email:archive | config archiv |
| ci:email:fromEmail | config fromEmai |
| ci:email:fromName | config fromNam |
| ci:email:userAgent | config userAgen |
| ci:email:mailPath | config mailPat |
| ci:email:protocol | config protoco |
| ci:email:SMTPHost | config SMTPHos |
| ci:email:SMTPUser | config SMTPUse |
| ci:email:SMTPPass | config SMTPPas |
| ci:email:SMTPPort | config SMTPPor |
| ci:email:SMTPTimeout | config SMTPTimeou |
| ci:email:SMTPKeepAlive | config SMTPKeepAliv |
| ci:email:SMTPCrypto | config SMTPCrypt |
| ci:email:wordWrap | config wordWra |
| ci:email:wrapChars | config wrapChar |
| ci:email:mailType | config mailTyp |
| ci:email:charset | config charse |
| ci:email:altMessage | config altMessag |
| ci:email:validate | config validat |
| ci:email:priority | config priorit |
| ci:email:newline | config newlin |
| ci:email:CRLF | config CRL |
| ci:email:DSN | config DS |
| ci:email:sendMultipart | config sendMultipar |
| ci:email:BCCBatchMode | config BCCBatchMod |
| ci:email:BCCBatchSize | config BCCBatchSiz |

### Encryptation

| Snippet | Purpose |
| --- | --- |
| ci:encryption:encrypt | $encrypter->encrypt |
| ci:encryption:decrypt | $encrypter->decrypt |
| ci:encryptation:key | $config->key |
| ci:encryptation:driver | $config->driver |
| ci:encryptation:blockSize | $config->blockSize |
| ci:encryptation:digest | $config->digest |
| ci:encryptation:rawData | $config->rawData |
| ci:encryptation:encryptKeyInfo | $config->encryptKeyInfo |
| ci:encryptation:authKeyInfo | $config->authKeyInfo |
| ci:encryptation:cipher | $config->cipher |

### File

| Snippet | Purpose |
| --- | --- |
| ci:file:getSize | $file->getSize |
| ci:file:getSizeByUnit | $file->getSizeByUnit |
| ci:file:guessExtension | $file->guessExtension |
| ci:file:getMimeType | $file->getMimeType |
| ci:file:getRandomName | $file->getRandomName |
| ci:file:move | $file->move |
| ci:file:getDestination | $file->getDestination |
| ci:file:hasMoved | $file->hasMoved |
| ci:file:getError | $file->getError |
| ci:file:getErrorString | $file->getErrorString |
| ci:file:getClientMimeType | $file->getClientMimeType |
| ci:file:getName | $file->getName |
| ci:file:getClientName | $file->getClientName |
| ci:file:getTempName | $file->getTempName |
| ci:file:getExtension | $file->getExtension |
| ci:file:getClientExtension | $file->getClientExtension |
| ci:file:isValid | $file->isValid |
| ci:file:store | $file->store |
| ci:files:get | $files->get |
| ci:files:set | $files->set |
| ci:files:add | $files->add |
| ci:files:addFiles | $files->addFiles |
| ci:files:addFile | $files->addFile |
| ci:files:removeFiles | $files->removeFiles |
| ci:files:removeFile | $files->removeFile |
| ci:files:addDirectories | $files->addDirectories |
| ci:files:addDirectory | $files->addDirectory |
| ci:files:removePattern | $files->removePattern |
| ci:files:retainPattern | $files->retainPattern |
| ci:files:count | $files->count |
| ci:files:getIterator | $files->getIterator |

### Image

| Snippet | Purpose |
| --- | --- |
| ci:image:withFile | $image->withFile |
| ci:image:getFile | $image->getFile |
| ci:image:getResource | $image->getResource |
| ci:image:withResource | $image->withResource |
| ci:image:resize | $image->resize |
| ci:image:crop | $image->crop |
| ci:image:convert | $image->convert |
| ci:image:rotate | $image->rotate |
| ci:image:flatten | $image->flatten |
| ci:image:flip | $image->flip |
| ci:image:text | $image->text |
| ci:image:reorient | $image->reorient |
| ci:image:getEXIF | $image->getEXIF |
| ci:image:fit | $image->fit |
| ci:image:getVersion | $image->getVersion |
| ci:image:save | $image->save |
| ci:image:getWidth | $image->getWidth |
| ci:image:getHeight | $image->getHeight |

### Pagination

| Snippet | Purpose |
| --- | --- |
| ci:pagination:links | $pager->links |
| ci:pagination:simpleLinks | $pager->simpleLinks |
| ci:pagination:makeLinks | $pager->makeLinks |
| ci:pagination:store | $pager->store |
| ci:pagination:setSegment | $pager->setSegment |
| ci:pagination:setPath | $pager->setPath |
| ci:pagination:getTotal | $pager->getTotal |
| ci:pagination:getPageCount | $pager->getPageCount |
| ci:pagination:getCurrentPage | $pager->getCurrentPage |
| ci:pagination:hasMore | $pager->hasMore |
| ci:pagination:getLastPage | $pager->getLastPage |
| ci:pagination:getFirstPage | $pager->getFirstPage |
| ci:pagination:getPageURI | $pager->getPageURI |
| ci:pagination:getNextPageURI | $pager->getNextPageURI |
| ci:pagination:getPreviousPageURI | $pager->getPreviousPageURI |
| ci:pagination:getPerPage | $pager->getPerPage |
| ci:pagination:getDetails | $pager->getDetails |
| ci:pagination:only | $pager->only |

### Redirect

| Snippet | Purpose |
| --- | --- |
| ci:redirect:to | redirect()->to |
| ci:redirect:route | redirect()->route |
| ci:redirect:back | redirect()->back |
| ci:redirect:withInput | redirect()->withInput |
| ci:redirect:with | redirect()->with |
| ci:redirect:withCookies | redirect()->withCookies |
| ci:redirect:withHeaders | redirect()->withHeaders |

### Request

| Snippet | Purpose |
| --- | --- |
| ci:request:getIPAddress | request->getIPAddress |
| ci:request:isValidIP | request->isValidIP |
| ci:request:getMethod | request->getMethod |
| ci:request:setMethod | request->setMethod |
| ci:request:withMethod | request->withMethod |
| ci:request:getUri | request->getUri |
| ci:request:getServer | request->getServer |
| ci:request:detectLocale | request->detectLocale |
| ci:request:detectPath | request->detectPath |
| ci:request:parseRequestURI | request->parseRequestURI |
| ci:request:parseQueryString | request->parseQueryString |
| ci:request:negotiate | request->negotiate |
| ci:request:is | request->is |
| ci:request:isCLI | request->isCLI |
| ci:request:isAJAX | request->isAJAX |
| ci:request:isSecure | request->isSecure |
| ci:request:setPath | request->setPath |
| ci:request:getPath | request->getPath |
| ci:request:setLocale | request->setLocale |
| ci:request:getLocale | request->getLocale |
| ci:request:getDefaultLocale | request->getDefaultLocale |
| ci:request:getVar | request->getVar |
| ci:request:getJSON | request->getJSON |
| ci:request:getJsonVar | request->getJsonVar |
| ci:request:getRawInput | request->getRawInput |
| ci:request:getRawInputVar | request->getRawInputVar |
| ci:request:getGet | request->getGet |
| ci:request:getPost | request->getPost |
| ci:request:getPostGet | request->getPostGet |
| ci:request:getGetPost | request->getGetPost |
| ci:request:getCookie | request->getCookie |
| ci:request:getUserAgent | request->getUserAgent |
| ci:request:getOldInput | request->getOldInput |
| ci:request:getFiles | request->getFiles |
| ci:request:getFileMultiple | request->getFileMultiple |
| ci:request:getFile | request->getFile |
| ci:request:removeRelativeDirectory | request->removeRelativeDirectory |
| ci:request:getOptions | request->getOptions |
| ci:request:getArgs | request->getArgs |
| ci:request:getSegments | request->getSegments |
| ci:request:getOption | request->getOption |
| ci:request:getOptionString | request->getOptionString |
| ci:request:setValidLocales | request->setValidLocales |

### Response

| Snippet | Purpose |
| --- | --- |
| ci:response:getStatusCode | response->getStatusCode |
| ci:response:setStatusCode | response->setStatusCode |
| ci:response:getReason | response->getReason |
| ci:response:getReasonPhrase | response->getReasonPhrase |
| ci:response:setDate | response->setDate |
| ci:response:setLastModified | response->setLastModified |
| ci:response:setLink | response->setLink |
| ci:response:setContentType | response->setContentType |
| ci:response:setJSON | response->setJSON |
| ci:response:getJSON | response->getJSON |
| ci:response:setXML | response->setXML |
| ci:response:noCache | response->noCache |
| ci:response:setCache | response->setCache |
| ci:response:send | response->send |
| ci:response:sendHeaders | response->sendHeaders |
| ci:response:sendBody | response->sendBody |
| ci:response:setCookie | response->setCookie |
| ci:response:hasCookie | response->hasCookie |
| ci:response:getCookie | response->getCookie |
| ci:response:deleteCookie | response->deleteCookie |
| ci:response:getCookies | response->getCookies |
| ci:response:getCookieStore | response->getCookieStore |
| ci:response:redirect | response->redirect |
| ci:response:download | response->download |
| ci:response:getCSP | response->getCSP |
| ci:response:respond | $this->respond |
| ci:response:fail | $this->fail |
| ci:response:respondCreated | $this->respondCreated |
| ci:response:respondDeleted | $this->respondDeleted |
| ci:response:respondUpdated | $this->respondUpdated |
| ci:response:respondNoContent | $this->respondNoContent |
| ci:response:failUnauthorized | $this->failUnauthorized |
| ci:response:failForbidden | $this->failForbidden |
| ci:response:failNotFound | $this->failNotFound |
| ci:response:failValidationError | $this->failValidationError |
| ci:response:failValidationErrors | $this->failValidationErrors |
| ci:response:failResourceExists | $this->failResourceExists |
| ci:response:failResourceGone | $this->failResourceGone |
| ci:response:failTooManyRequests | $this->failTooManyRequests |
| ci:response:failServerError | $this->failServerError |
| ci:response:setResponseFormat | $this->setResponseFormat |

### Routes

| Snippet | Purpose |
| --- | --- |
| ci:routes:get | $routes->get |
| ci:routes:post | $routes->post |
| ci:routes:put | $routes->put |
| ci:routes:delete | $routes->delete |
| ci:routes:head | $routes->head |
| ci:routes:patch | $routes->patch |
| ci:routes:options | $routes->options |
| ci:routes:cli | $routes->cli |
| ci:routes:add | $routes->add |
| ci:routes:view | $routes->view |
| ci:routes:addPlaceholder | $routes->addPlaceholder |
| ci:routes:presenter | $routes->presenter |
| ci:routes:resource | $routes->resource |
| ci:routes:match | $routes->match |
| ci:routes:addRedirect | $routes->addRedirect |
| ci:routes:map | $routes->map |
| ci:routes:setPrioritize | $routes->setPrioritize |
| ci:routes:setTranslateURIDashes | $routes->setTranslateURIDashes |
| ci:routes:setAutoRoute | $routes->setAutoRoute |
| ci:routes:setDefaultNamespace | $routes->setDefaultNamespace |
| ci:routes:setDefaultController | $routes->setDefaultController |
| ci:routes:setDefaultMethod | $routes->setDefaultMethod |
| ci:routes:environment | $routes->environment |
| ci:routes:group | $routes->group |
| ci:routes:loadRoutes | $routes->loadRoutes |
| ci:routes:getPlaceholders | $routes->getPlaceholders |
| ci:routes:set404Override | $routes->set404Override |
| ci:routes:get404Override | $routes->get404Override |
| ci:routes:setDefaultConstraint | $routes->setDefaultConstraint |
| ci:routes:getDefaultController | $routes->getDefaultController |
| ci:routes:getDefaultMethod | $routes->getDefaultMethod |
| ci:routes:getDefaultNamespace | $routes->getDefaultNamespace |
| ci:routes:shouldTranslateURIDashes | $routes->shouldTranslateURIDashes |
| ci:routes:shouldAutoRoute | $routes->shouldAutoRoute |
| ci:routes:getRoutes | $routes->getRoutes |
| ci:routes:getRoutesOptions | $routes->getRoutesOptions |
| ci:routes:getHTTPVerb | $routes->getHTTPVerb |
| ci:routes:setHTTPVerb | $routes->setHTTPVerb |
| ci:routes:isRedirect | $routes->isRedirect |
| ci:routes:getRedirectCode | $routes->getRedirectCode |
| ci:routes:reverseRoute | $routes->reverseRoute |
| ci:routes:isFiltered | $routes->isFiltered |
| ci:routes:getFilterForRoute | $routes->getFilterForRoute |
| ci:routes:getFiltersForRoute | $routes->getFiltersForRoute |
| ci:routes:resetRoutes | $routes->resetRoutes |
| ci:routes:getRegisteredControllers | $routes->getRegisteredControllers |
| ci:routes:useSupportedLocalesOnly | $routes->useSupportedLocalesOnly |
| ci:routes:shouldUseSupportedLocalesOnly | $routes->shouldUseSupportedLocalesOnly |

### Session

| Snippet | Purpose |
| --- | --- |
| ci:session:get | $session->get |
| ci:session:set | $session->set |
| ci:session:has | $session->has |
| ci:session:push | $session->push |
| ci:session:remove | $session->remove |
| ci:session:markAsFlashdata | $session->markAsFlashdata |
| ci:session:unmarkFlashdata | $session->unmarkFlashdata |
| ci:session:getFlashKeys | $session->getFlashKeys |
| ci:session:setFlashdata | $session->setFlashdata |
| ci:session:getFlashdata | $session->getFlashdata |
| ci:session:keepFlashdata | $session->keepFlashdata |
| ci:session:markAsTempdata | $session->markAsTempdata |
| ci:session:unmarkTempdata | $session->unmarkTempdata |
| ci:session:setTempdata | $session->setTempdata |
| ci:session:getTempdata | $session->getTempdata |
| ci:session:removeTempdata | $session->removeTempdata |
| ci:session:getTempKeys | $session->getTempKeys |
| ci:session:setSaveHandler | $session->setSaveHandler |
| ci:session:startSession | $session->startSession |
| ci:session:setCookie | $session->setCookie |
| ci:session:start | $session->start |
| ci:session:stop | $session->stop |
| ci:session:regenerate | $session->regenerate |
| ci:session:destroy | $session->destroy |

### Time

| Snippet | Purpose |
| --- | --- |
| ci:time:now | Time::now |
| ci:time:parse | Time::parse |
| ci:time:today | Time::today |
| ci:time:yesterday | Time::yesterday |
| ci:time:tomorrow | Time::tomorrow |
| ci:time:createFromDate | Time::createFromDate |
| ci:time:createFromTime | Time::createFromTime |
| ci:time:create | Time::create |
| ci:time:createFromFormat | Time::createFromFormat |
| ci:time:createFromTimestamp | Time::createFromTimestamp |
| ci:time:createFromInstance | Time::createFromInstance |
| ci:time:instance | Time::instance |
| ci:time:setTestNow | Time::setTestNow |
| ci:time:hasTestNow | Time::hasTestNow |
| ci:time:toDateTime | $time->toDateTime |
| ci:time:getYear | $time->getYear |
| ci:time:getMonth | $time->getMonth |
| ci:time:getDay | $time->getDay |
| ci:time:getHour | $time->getHour |
| ci:time:getMinute | $time->getMinute |
| ci:time:getSecond | $time->getSecond |
| ci:time:getDayOfWeek | $time->getDayOfWeek |
| ci:time:getDayOfYear | $time->getDayOfYear |
| ci:time:getWeekOfMonth | $time->getWeekOfMonth |
| ci:time:getWeekOfYear | $time->getWeekOfYear |
| ci:time:getAge | $time->getAge |
| ci:time:getQuarter | $time->getQuarter |
| ci:time:getDst | $time->getDst |
| ci:time:getLocal | $time->getLocal |
| ci:time:getUtc | $time->getUtc |
| ci:time:getTimezoneName | $time->getTimezoneName |
| ci:time:setYear | $time->setYear |
| ci:time:setMonth | $time->setMonth |
| ci:time:setDay | $time->setDay |
| ci:time:setHour | $time->setHour |
| ci:time:setMinute | $time->setMinute |
| ci:time:setSecond | $time->setSecond |
| ci:time:setTimezone | $time->setTimezone |
| ci:time:setTimestamp | $time->setTimestamp |
| ci:time:addSeconds | $time->addSeconds |
| ci:time:addMinutes | $time->addMinutes |
| ci:time:addHours | $time->addHours |
| ci:time:addDays | $time->addDays |
| ci:time:addMonths | $time->addMonths |
| ci:time:addYears | $time->addYears |
| ci:time:subSeconds | $time->subSeconds |
| ci:time:subMinutes | $time->subMinutes |
| ci:time:subHours | $time->subHours |
| ci:time:subDays | $time->subDays |
| ci:time:subMonths | $time->subMonths |
| ci:time:subYears | $time->subYears |
| ci:time:toDateTimeString | $time->toDateTimeString |
| ci:time:toDateString | $time->toDateString |
| ci:time:toFormattedDateString | $time->toFormattedDateString |
| ci:time:toTimeString | $time->toTimeString |
| ci:time:toLocalizedString | $time->toLocalizedString |
| ci:time:equals | $time->equals |
| ci:time:sameAs | $time->sameAs |
| ci:time:isBefore | $time->isBefore |
| ci:time:isAfter | $time->isAfter |
| ci:time:humanize | $time->humanize |
| ci:time:difference | $time->difference |
| ci:time:getUTCObject | $time->getUTCObject |
| ci:time:getCalendar | $time->getCalendar |

### Validation

| Snippet | Purpose |
| --- | --- |
| ci:validation:setRule | $validation->setRule |
| ci:validation:setRules | $validation->setRules |
| ci:validation:withRequest | $validation->withRequest |
| ci:validation:run | $validation->run |
| ci:validation:reset | $validation->reset |
| ci:validation:check | $validation->check |
| ci:validation:getRuleGroup | $validation->getRuleGroup |
| ci:validation:setRuleGroup | $validation->setRuleGroup |
| ci:validation:getError | $validation->getError |
| ci:validation:hasError | $validation->hasError |
| ci:validation:listErrors | $validation->listErrors |
| ci:validation:showError | $validation->showError |
| ci:validation:getErrors | $validation->getErrors |
| ci:validation:setError | $validation->setError |
| ci:validation:loadRuleGroup | $validation->loadRuleGroup |
| ci:validation:getValidated | $validation->getValidated |
| ci:rule:alpha | alpha |
| ci:rule:alpha_space | alpha_space |
| ci:rule:alpha_dash | alpha_dash |
| ci:rule:alpha_numeric | alpha_numeric |
| ci:rule:alpha_numeric_space | alpha_numeric_space |
| ci:rule:alpha_numeric_punct | alpha_numeric_punct |
| ci:rule:decimal | decimal |
| ci:rule:differs | differs |
| ci:rule:exact_length | exact_length |
| ci:rule:greater_than | greater_than |
| ci:rule:greater_than_equal_to | greater_than_equal_to |
| ci:rule:hex | hex |
| ci:rule:if_exist | if_exist |
| ci:rule:in_list | in_list |
| ci:rule:integer | integer |
| ci:rule:is_natural | is_natural |
| ci:rule:is_natural_no_zero | is_natural_no_zero |
| ci:rule:is_not_unique | is_not_unique |
| ci:rule:is_unique | is_unique |
| ci:rule:less_than | less_than |
| ci:rule:less_than_equal_to | less_than_equal_to |
| ci:rule:matches | matches |
| ci:rule:max_length | max_length |
| ci:rule:min_length | min_length |
| ci:rule:not_in_list | not_in_list |
| ci:rule:numeric | numeric |
| ci:rule:regex_match | regex_match |
| ci:rule:permit_empty | permit_empty |
| ci:rule:required | required |
| ci:rule:required_with | required_with |
| ci:rule:required_without | required_without |
| ci:rule:string | string |
| ci:rule:timezone | timezone |
| ci:rule:valid_base64 | valid_base64 |
| ci:rule:valid_json | valid_json |
| ci:rule:valid_email | valid_email |
| ci:rule:valid_emails | valid_emails |
| ci:rule:valid_ip | valid_ip |
| ci:rule:valid_url | valid_url |
| ci:rule:valid_url_strict | valid_url_strict |
| ci:rule:valid_date | valid_date |
| ci:rule:valid_cc_number | valid_cc_number |
| ci:rule:uploaded | uploaded |
| ci:rule:max_size | max_size |
| ci:rule:max_dims | max_dims |
| ci:rule:mime_in | mime_in |
| ci:rule:ext_in | ext_in |
| ci:rule:is_image | is_image |

### View

| Snippet | Purpose |
| --- | --- |
| ci:view:render | $view->render |
| ci:view:renderString | $view->renderString |
| ci:view:excerpt | $view->excerpt |
| ci:view:setData | $view->setData |
| ci:view:setVar | $view->setVar |
| ci:view:resetData | $view->resetData |
| ci:view:getData | $view->getData |
| ci:view:extend | $this->extend |
| ci:view:section | $this->section |
| ci:view:endSection | $this->endSection |
| ci:view:renderSection | $this->renderSection |
| ci:view:include | $this->include |
| ci:view:getPerformanceData | $view->getPerformanceData |

## Connect with me

[![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge&logo=github)](https://github.com/ManuelGil)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- [NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)
- [NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
- [Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)
- [T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)
- [CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)
- [CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
- [CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)
- [Moodle Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-moodle-snippets)
- [Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)

## Community

- CodeIgniter Hispano [CiHispano](https://www.cihispano.org/)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)

## Authors

- **Manuel Gil** - _Owner_ - [ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/vscode-codeigniter4-snippets/contributors) who participated in this project.

## License

CodeIgniter 4 Snippets for VSCode is licensed under the MIT License - see the [MIT License](https://opensource.org/licenses/MIT) for details.
